### Responses/Fixes for Penetration Test Report 2020-04-07

#### 5.1 Disclosure of Origin IP

Server no longer used, we do not run a public facing Confluence Server on our domains.

#### 5.2 Cleartext Submission of Password

Server no longer used, we do not run a public facing Confluence Server on our domains.

#### 5.3 Old Versions of TLS Supported

Server no longer used, we do not run a public facing Confluence Server on our domains.

#### 5.4 Content Sniffing not disabled

app.diagrams.net, confluence.draw.io and jira.draw.io deliver header `X-Content-Type-Options: nosniff`

#### 5.5 Browser Cross Site Scripting filter missing

app.diagrams.net, confluence.draw.io and jira.draw.io deliver header `X-XSS-Protection: 1; mode=block`

#### 5.6 Strict Transport Security not enforced

We could not recreate this issue. We contacted the author, but they saw HSTS across all sub-domains. HSTS has been enabled since diagrams.net went live and since 2016 on draw.io.

#### 5.7 Information Disclosure

Server no longer used, we do not run a public facing Confluence Server on our domains.
