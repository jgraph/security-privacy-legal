### Responses/Fixes for Penetration Test Report 2018-08-18

#### 5.1 Out of band Resource Load leads to SSRF and access token

This was an SSRF attack via the proxy servlet that enabled the attacker to invoke commands on the Google App Engine project serving draw.io. The project automatically creates a service account with full permissions to the Google Cloud project.

The mitigations for this were:

1. Explicitly block proxy requests that contain the string "metadata.google.internal". This is the only domain the commands can be invoked on.
2. Restrict permissions of the service account down to the absolute minimum required for the project to be able to function. This was completed down to a bare minimum permissions set that meant an attack could not write or read anything internal.
3. Since 1 relied on the URL staying constant and 2 was subject to manual error, the proxy functionality was entirely moved from Google App Engine onto Cloudflare, which acts as CDN. Cloudflare has no equivalent attack in the workers functionality.

#### 5.2 Reverse Tabnabbing

Fixes:

https://github.com/jgraph/mxgraph2/commit/d9e8e3177b4baf6b0361df5bf7750645ecc12f12

https://github.com/jgraph/mxgraph2/commit/2c3e347983768f6130c69e9fcb1a52b216b3f398

https://github.com/jgraph/mxgraph2/commit/9a5a9423545162b71df99d61be77a761991c848e

#### 5.3 Weak Cipher Suites

TLS 1.2 was set as the minimum TLS version, but beyond that we don't agree with this being medium criticality. The client is reponsible for sending its preferred order of suites and Cloudflare's preferred server order will agree a strong suite to any modern browser. As long as the range of suites and preferred order provides a strong suite to recent versions of every supported modern browser (we don't include IE 11 as modern), we deem it the responibility of the user to use a secure browser.

Additionally, this would be an ongoing process and a configuration would only be correct until another suite were deemed weak.

#### 5.4 SSH Bruteforce

