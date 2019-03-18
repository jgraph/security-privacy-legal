# Information Security Policy

- Owner:    David Benson
- Company:    JGraph Ltd
- Version:    1.1
- Published:    29 November 2018
- Status:        Published


### Background Information

JGraph Ltd is an open source technology stack for building diagramming applications, and the world’s most widely used browser-based end-user diagramming application draw.io.

JGraph Ltd aims to provide free, high quality diagramming software for everyone.

### Purpose

This policy defines the requirements for protecting JGraph Ltd information assets and systems, including physical and digital forms, throughout their lifecycle, to support our people, our customers and processes with a standard approach to managing and addressing information security related threats and events at JGraph Ltd.

### Goals

- Define a simple and structured baseline of security controls to which JGraph Ltd adheres.

### Scope

This policy applies to all personnel, including contractors, of JGraph Ltd and all activities relating to the use, handling, management or control of information assets and systems controlled by JGraph Ltd.

### Roles and Responsibilities

Roles and responsibilities of personnel at JGraph Ltd are proactively identified and assessed, in alignment with the business requirements and information security best practices.

- Personnel of JGraph Ltd follow and operate within all relevant regulations, standards, and legislation, including this standard to ensure the safeguarding of JGraph Ltd information assets.
- Report any detected or suspected deviation from this information security standard to the designated Information Security Manager.

### Access Control

Access to information assets and systems by personnel of JGraph Ltd is proactively identified, managed, and assessed in alignment with applying the principle of least privilege and need to know basis.

- Develop, implement and maintain an __access control procedure__ for information assets and systems where access to those information assets and systems presents a material risk.
- Protect JGraph Ltd information assets and systems in accordance with the defined __access control procedure__.
- Identify and provide unique credential sets for each personnel requiring access to JGraph Ltd information assets.
- Develop, implement and maintain a strong credentials in the form of one or more of the following:
   * Complex passwords (12+ characters consisting of upper, lower, numeric, and special characters).
   * Biometrics (fingerprint, iris, face, voice)
   * Tokens (soft - Microsoft Authenticator, Google Authenticator, OTP / TOTP, hard - RSA SecurID, Yubikeys)

### Human Resources

Risks associated with employment of personnel of JGraph Ltd are proactively identified and assessed in alignment with ISO/IEC 27001:2013 Annex A, A.7 Human resource security.

- Conduct and complete background verification checks for all personnel prior to the commencement of employment.
- Define, develop and enrol all personnel in the __security awareness and training program__.
- Define and document metrics for measuring the success of the security awareness and training program.
- Assess and evaluate the success factors of the __security awareness and training program__.

### Information Management

Operational activities associated with the handling of information are performed in accordance with JGraph Ltd policies and procedures.

- Classify and handle information as defined by the __information classification and handling policy__ and __data stewardship and governance policy__.

### Information Assets

Information assets and systems are identified, recorded and routinely assessed to ensure appropriate classification labels have been assigned in an __information asset register__.

- Define, document and assign an __owner of information assets and systems__.
- Define, document and assign a classification label to information assets in accordance with the __information classification and handling policy__.
- Maintain and update information assets and systems and their security in accordance with this policy.

### Cryptography and Encryption

Implementation of cryptography and encryption is controlled to protect information assets and systems.

- Use encryption and cryptography technology that is currently considered strong by industry standards.
  * See the following for more details:
https://csrc.nist.gov/Projects/Cryptographic-Algorithm-Validation-Program
- Encrypt and protect all authentication and authorisation communications.
- Identify, protect and encrypt all personally identifiable information at rest and in transit.
- Identify, review and analyse infrastructure configurations and policies to determine appropriate strong encryption requirements are implemented.
  * Example 1: SMTP should require TLS for communications for each mail relay used and refuse delivery where TLS is not available.

### Operations

Operational processes and activities are delivered and reviewed for conformance with information security practices.

- __Operational processes__ are updated in accordance with the reviews for the achievement of a good information security programme.
- Define, document and maintain information security aspects of operational processes and procedures undertaken as business-as-usual activities.
- Employ verification of information security controls and approaches to all items impacting information assets and systems through the __change management process__.
- Define, document and maintain appropriate processes for the monitoring of networked assets to ensure threats are identified.
- Adhere to the __Endpoint Security Policy__.

### Communications

Communication of information assets is performed in a secure and safe manner to ensure compliance with the __information classification and handling policy__.

- Protect information assets prior to and during transit using encryption and cryptographic controls in accordance with the __information classification and handling policy__.

### System Acquisition and Development

The potential dangers of implementing and utilising systems without appropriate information security controls applied are proactively detected and analysed to align with the __risk framework__.

- Define, document and maintain a __systems development lifecycle__ which implements information security practices within each phase.
- Apply and comply with the required steps as defined within the __systems development lifecycle__.

### Supplier and Third-Party Relationships

Suppliers and third-party entities which JGraph Ltd works with and obtains services from are routinely assessed and reviewed for good information security practices to ensure alignment with acceptable information security practices.

- Adhere to the __Third Party Management Policy__.

### Incident Management

The potential dangers of information security incidents and associated events that impact JGraph Ltd or its stakeholders are proactively identified, managed and treated in order to protect JGraph Ltd, its people and stakeholders.

- Define, document and implement measures to identify and alert on suspected or actual information security events.
- Report suspected and actual information security incidents to the designated information security manager.
- Triage and implement measures to address, reduce and recover from information security incidents.

### Business Continuity and Disaster Recovery

Delivery of a business continuity and disaster recovery plan will enable JGraph Ltd to continue operating and enable the business to perform in the event of a severe incident or event.

- Define, document and maintain the information security controls applied to systems identified as critical to business continuity and disaster recovery.
- Define, document and maintain information security controls and practices within the business continuity and disaster recovery plans.

### Compliance

Information assets and systems are routinely audited to confirm compliance with JGraph Ltd Standards, regulatory, legislative and contractual requirements.

- Identify, document and update all information security-focused compliance requirements for each information asset and system.

### Remote Access and Teleworking

Remote access provides an effective and secure method of operating and accessing JGraph Ltd information assets and systems.

- Implement information security controls commensurate with the criticality of information assets and systems at remote sites and remote access users (teleworking).
- Adhere to the __Endpoint Security Policy__.
