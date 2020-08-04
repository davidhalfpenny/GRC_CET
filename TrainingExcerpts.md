# GRC Standards And Training

This document contains details of the standards and other compliance schemes that the GRC practice have capability around and where they intersect with the Capability, Education & Training practice.

It's written so that you can up-sell GRC customers with CET products and services.

Excerpts from the standards are included, but you may wish to consult the standard for full context.

*Education needs/gap analysis??*
| Shortname                                                 | Name                                                                                 | Education Requirement |
|-----------------------------------------------------------|--------------------------------------------------------------------------------------|-----------------------|
| PCI-DSS                                                   | Payment Card Industry - Data Security Standard                                       | Yes                   |
| ISM                                                       | Australian Government Information Security Manual                                    | Yes                   |
| ISMS (ISO 27001) - Information Security Management System |                                                                                      |                       |
| BCMS (ISO 22301) - Business Continuity Management System  |                                                                                      |                       |
| IMS (Integrated Management system) ???                    |                                                                                      |                       |
| PSPF/ISM                                                  |                                                                                      |                       |
| APRA CPS 234                                              | Australian Prudential Regulation Authority Information Security Prudential Standard  | Yes                   |
| ISO 14001                                                 |                                                                                      |                       |
| Essential 8                                               |                                                                                      |                       |
| PSPF                                                      | Protective Security Policy Framework                                                 | Yes                   |
| SOC 2/3                                                   |                                                                                      |                       |
| GNGB                                                      |                                                                                      |                       |
| SACSF                                                     |                                                                                      |                       |
| VPDSF                                                     |                                                                                      |                       |
| NSW CSP                                                   |                                                                                      |                       |
| IS18                                                      |                                                                                      |                       |
| NIST CSF                                                  |                                                                                      |                       |
| C2M2                                                      | Cybersecurity Capability Maturity Model                                              | No                    |
| CMMC                                                      | Cybersecurity Maturity Model Certification                                           | Yes                   |























# Compliance Schemes We Work In

## PCI-DSS

### What is PCI-DSS?
**Payment Card Industry - Data Security Standard**

Other PCI standards/frameworks (such as PA-DSS/Software Security Framework) don't mandate or recommend any specific training, but do mention that assessors need to be trained, not only in the PCI material but also in the area the standard/framework relates to. For example, the software security assessors need to understand software development and the forensic investigators need to understand forensics.

### What does it say about education and training?

The following excerpts are from PCI-DSS Version 3.2.1

#### Requirement 6.5
**PCI DSS Requirements**
>Address common coding vulnerabilities in software-development processes as follows:
>• **Train developers at least annually in up-to-date secure coding techniques, including how to avoid common coding vulnerabilities.**
...

**Testing Procedures**
>**6.5.a Examine software-development policies and procedures to verify that up-to-date training in secure coding techniques is required for developers at least annually, based on industry best practices and guidance.**
>**6.5.b Examine records of training to verify that software developers receive up-to-date training on secure coding techniques at least annually, including how to avoid common coding vulnerabilities.**
...

**Guidance**
...
>**Application developers should be properly trained** to identify and resolve issues related to these (and other) common coding vulnerabilities. Having staff knowledgeable of secure coding guidelines should minimize the number of security vulnerabilities introduced through poor coding practices. Training for developers may be provided in-house or by third parties and should be applicable for technology used.
>As industry-accepted secure coding practices change, **organizational coding practices and developer training should likewise be updated** to address new threats—for example, memory scraping attacks.
...

#### Requirement 9.9
**PCI DSS Requirements**
>Protect devices that capture payment card data via direct physical interaction with the card from tampering and substitution.
...

**Testing Procedures**
>9.9 Examine documented policies and procedures to verify they include:
...
>**Training personnel to be aware of suspicious behavior and to report tampering or substitution of devices.**
...

**Guidance**
...

#### Requirement 9.9.3
**PCI DSS Requirements**
>**Provide training for personnel to be aware of attempted tampering or replacement of devices**. Training should include the following:
>• Verify the identity of any third-party persons claiming to be repair or maintenance personnel, prior to granting them access to modify or troubleshoot devices.
>• Do not install, replace, or return devices without verification.
>• Be aware of suspicious behavior around devices (for example, attempts by unknown persons to unplug or open devices).
>• Report suspicious behavior and indications of device tampering or substitution to appropriate personnel (for example, to a manager or security officer).
...

**Testing Procedures**
>**9.9.3.a Review training materials for personnel at point-of-sale locations to verify they include training in the following:**
...
>**9.9.3.b Interview a sample of personnel at point-of-sale locations to verify they have received training and are aware of the procedures for the following:**
...

**Guidance**
...

#### Requirement 12.6
**PCI DSS Requirements**
>**Implement a formal security awareness program to make all personnel aware of the cardholder data security policy and procedures.**

**Testing Procedures**
>**12.6.a Review the security awareness program to verify it provides awareness to all personnel about the cardholder data security policy and procedures .**
>**12.6.b Examine security awareness program procedures and documentation and perform the following:**
...

**Guidance**
...

#### Requirement 12.6.1
**PCI DSS Requirements**
>**Educate personnel upon hire and at least annually.**
...

**Testing Procedures**
>**12.6.1.a Verify that the security awareness program provides multiple methods of communicating awareness and educating personnel (for example, posters, letters, memos, web-based training, meetings, and promotions).**
>**12.6.1.b Verify that personnel attend security awareness training upon hire and at least annually.**
>**12.6.1.c Interview a sample of personnel to verify they have completed awareness training and are aware of the importance of cardholder data security.**

**Guidance**
>If the security awareness program does not include periodic refresher sessions, key security processes and procedures may be forgotten or bypassed, resulting in exposed critical resources and cardholder data.

#### Requirement 12.10.4
**PCI DSS Requirements**
>**Provide appropriate training to staff with security breach response responsibilities.**

**Testing Procedures**
>**12.10.4 Verify through observation, review of policies, and interviews of responsible personnel that staff with responsibilities for security breach response are periodically trained.**

**Guidance**
...

#### Requirement A3
**PCI DSS Requirements**
>**Provide up-to-date PCI DSS and/or information security training at least annually to personnel with PCI DSS compliance responsibilities (as identified in A3.1.3).**

**Testing Procedures**
>**A3.1.4.a Examine information security policies and procedures to verify that PCI DSS and/or information security training is required at least annually for each role with PCI DSS compliance responsibilities.**
>**A3.1.4.b Interview personnel and examine certificates of attendance or other records to verify that personnel with PCI DSS compliance responsibility receive up-to-date PCI DSS and/or similar information security training at least annually.**

**Guidance**
>Personnel responsible for PCI DSS compliance have specific training needs exceeding that which is typically provided by general security awareness training. Individuals with PCI DSS compliance responsibilities should receive specialized training that, in addition to general awareness of information security, focuses on specific security topics, skills, processes, or methodologies that must be followed for those individuals to perform their compliance responsibilities effectively.
>Training may be offered by third parties—for example, SANS or PCI SSC (PCI Awareness, PCIP, and ISA), payment brands, and acquirers—or training may be internal. Training content should be applicable for the particular job function and be current to include the latest security threats and/or version of PCI DSS.
>For additional guidance on developing appropriate security training content for specialized roles, refer to the PCI SSC’s Information Supplement on Best Practices for Implementing a Security Awareness Program.

## ISM

### What is ISM?
**Australian Government Information Security Manual**


### What does it say about education and training?

The following excerpts are from the June 2020 edition

#### Cyber Security Principles
> P13: Personnel are provided with ongoing cyber security awareness training.

#### Guidelines for Personnel Security
**Cyber security awareness training**

**Providing cyber security awareness training**
>Organisations should ensure that ongoing cyber security awareness training is provided to all personnel in order to assist them in understanding their security responsibilities. The content of cyber security awareness training will depend on the objectives of the organisation; however, personnel with responsibilities beyond that of a standard user will require tailored content to meet their needs.

>**Security Control: 0252; Revision: 6; Updated: Jun-20; Applicability: O, P, S, TS**
>Cyber security awareness training is undertaken annually by all personnel and covers:
* the purpose of the cyber security awareness training
* security appointments and contacts within the organisation
* authorised use of systems and their resources
* protection of systems and their resources
* reporting of cyber security incidents and suspected compromises of systems and their resources.

>**Security Control: 1565; Revision: 0; Updated: Jun-20; Applicability: O, P, S, TS**
>Tailored privileged user training is undertaken annually by all privileged users.

**Reporting suspicious contact via online services**
>Online services such as email, internet forums, instant messaging apps and direct messaging on social media can all be used by an adversary in an attempt to elicit information from personnel. As such, personnel should be advised of what constitutes suspicious contact via online services and how to report it.

>**Security Control: 0817; Revision: 4; Updated: Jan-20; Applicability: O, P, S, TS**
>Personnel are advised of what suspicious contact via online services is and how to report it.

**Posting work information to online services**
>Personnel should be advised to take special care not to post work information to online services unless authorised to do so, especially in internet forums and on social media. Even information that appears to be benign in isolation could, along with other information, have a considerable security impact. In addition, to ensure that personal opinions of individuals are not interpreted as official policy, personnel should be advised to maintain separate work and personal accounts for online services, especially when using social media.

>**Security Control: 0820; Revision: 5; Updated: Jan-20; Applicability: O, P, S, TS**
Personnel are advised to not post work information to unauthorised online services and to report cases where such information is posted.
>**Security Control: 1146; Revision: 2; Updated: Sep-18; Applicability: O, P, S, TS**
Personnel are advised to maintain separate work and personal accounts for online services.

**Posting personal information to online services**
>Personnel should be advised that any personal information they post to online services, such as social media, could be used by an adversary to develop a detailed profile of their lifestyle in order to build a relationship with them. This relationship could then be used to attempt to elicit information or influence them to undertake specific actions, such as opening malicious emails or visiting malicious websites. Furthermore, encouraging personnel to use the privacy settings of online services can minimise who can view their information and interactions on such services.

>**Security Control: 0821; Revision: 3; Updated: Oct-19; Applicability: O, P, S, TS**
Personnel are advised of security risks associated with posting personal information to online services and are encouraged to use any available privacy settings to restrict who can view such information.

**Sending and receiving files via online services**
>When personnel send and receive files via online services, such as instant messaging apps and social media, they often bypass security controls put in place to detect and quarantine malicious code. Advising personnel to only send and receive files via authorised online services will ensure files are appropriately protected and scanned for malicious code.

>**Security Control: 0824; Revision: 2; Updated: Sep-18; Applicability: O, P, S, TS**
Personnel are advised not to send or receive files via unauthorised online services.

#### Gateway administration
...
>Providing system administrators with formal training will ensure they are fully aware of, and accept, their roles and responsibilities regarding the management of gateways. Formal training could be through commercial providers, or simply through Standard Operating Procedures or reference documents bound by a formal agreement.
...
>**Security Control: 0612; Revision: 4; Updated: Sep-18; Applicability: O, P, S, TS**
>System administrators are formally trained to manage gateways.

#### Cross Domain Solutions
...
#### User training
>It is important that users know how to use a CDS securely. This can be achieved via training before access is granted, and reinforced by logon banners and awareness messages.

>**Security Control: 0610; Revision: 6; Updated: Apr-19; Applicability: O, P, S, TS**
>Users are trained on the secure use of a CDS before access to the CDS is granted.

## APRA CPS 234

### What is APRA CPS 234?
**Australian Prudential Regulation Authority Information Security Prudential Standard**


### What does it say about education and training?
The standard says nothing about education and training, but the Prudential Practice Guide (CPG 234 Information Security) document has the following *recommendations* for education and training:

#### Attachment B: Training and awareness
> 1. An APRA-regulated entity could benefit from developing a training and information security awareness program. This would typically communicate to personnel (staff, contractors and third parties) regarding information security practices, policies and other expectations as well as providing material to assist the Board and other governing bodies to execute their duties. Sound practice would involve tracking training undertaken and testing the understanding of relevant information security policies, both on commencement and periodically.

> 2. An APRA-regulated entity would regularly educate users, including both internal and third party staff, as to their responsibilities regarding securing information assets. Common areas covered would typically include:
a) personal versus corporate use of information assets;
b) email usage, internet usage (including social networking) and malware11 protection;
c) physical protection, remote computing and usage of mobile devices;
d) awareness of common attack techniques targeted at personnel and facilities (e.g. social engineering, tailgating);
e) access controls, including standards relating to passwords and other authentication requirements;
f) responsibilities with respect to any end-user developed/configured software (including spreadsheets, databases and office automation);
g) expectations of staff where bring-your-own-device is an option;
h) handling of sensitive data; and
i) reporting of information security incidents and concerns.

> 3. An APRA-regulated entity would typically require users to adhere to appropriate information security policies pertinent to their roles and responsibilities. At a minimum, all users would typically be required to periodically sign-off on these policies as part of the terms and conditions of their employment or contractual agreements.

#### Common information reported to Boards and management
> **Education**
> * Informational and awareness material
> * Results of training and awareness sessions


## PSPF

### What is PSPF?
** **


### What does it say about education and training?

#### C.1 Accountable authority role and responsibilities

**5. The accountable authority is responsible for:**
...
> c. providing security awareness training for personnel (including contractors) about their security responsibilities

####Security Awareness Training

The core requirement mandates that entities ensure personnel and contractors are provided with sufficient information on their responsibilities under the PSPF, and their entity-specific security responsibilities.

The core requirement is supported by:

Requirement 3 that mandates all personnel, including contractors, are provided with security awareness training upon engagement and annual refresher training
Requirement 4 that mandates all personnel in specialist and high-risk positions, including contractors and security incident investigators, must be provided with specific security awareness training targeted to the scope and nature of the position.
Security awareness training is an important element of protective security and supports implementation of physical, information and personnel security policies, practices and procedures. The Attorney‑General's Department recommends that entities use their security plan to identify areas to include in their security awareness training program.

Security awareness training is most effective when it:

delivers an ongoing security awareness program to inform and regularly remind individuals of security responsibilities, issues and concerns
briefs personnel on the access privileges and prohibitions attached to their security clearance level prior to being given access, or when required in the security clearance renewal cycle
ensures that personnel who have specific security duties receive appropriate and up-to-date training
fulfils security clearance renewal briefing requirements for all personnel and contracted service providers who hold a security clearance of Negative Vetting Level 1 or higher
clearly communicates to all personnel, including contractors, the entity's protective security practices and procedures.
Entities are encouraged to strengthen security awareness through:

campaigns that address the ongoing needs of the entity and the specific needs of sensitive areas, activities or periods of time
security instructions and reminders via publications, electronic bulletins and visual displays such as posters
protective security-related questions in personnel selection interviews
drills and exercises
inclusion of security awareness and attitudes in the entity performance management program.
Delivery of security awareness training
The Attorney-General's Department recommends that the CSO decide on the most appropriate delivery method to ensure consistent delivery of training within their entity or those entities they provide training to as part of a lead security arrangement.

The Attorney-General's Department recommends that in meeting Requirement 3 to provide security awareness training upon engagement and annually thereafter, entities also provide:

advice to personnel on entity-specific asset management and loss reporting procedures prior to them taking custody of assets, including entity fraud measures
a safety handbook for all personnel that includes emergency response guidelines and contacts, as well as entity-specific safety requirements and procedures
regular safety exercises and drills for personnel
personnel with specific emergency safety or security roles with regular training, as well as assessment of their ongoing competency
specialist training to meet entity-specific risks
targeted security awareness training where the entity has identified a need based on their risk profile, or when the entity has an increased or changed threat environment.
If an entity elects to use an outsourced training provider to deliver the security awareness training, the Attorney-General's Department recommends they have sufficient knowledge of the PSPF and expertise in delivering adult education.

**Content of security awareness training**
Table 6 Content of security awareness training
https://www.protectivesecurity.gov.au/governance/management-structures-and-responsibilities/Pages/default.aspx#c.9

Security awareness refresher training
Under Requirement 3, entities are required to provide personnel with security awareness training annually. The CSO determines the form (eg in person, online), scope of coverage and content required for the annual training requirement to maintain sufficient awareness of security requirements and obligations to protect the entity's people, information and assets.

The Attorney General's Department recommends that the CSO consider:

the entity's risk and current threat environment
goals and objectives of the entity's security plan
any identified inadequacies in previous methods of training or consistent failure to understand content, particularly when systemic or reoccurring security incidents indicate potential vulnerabilities in awareness training.



## CMMC

### What is CMMC?
**Cybersecurity Maturity Model Certification**


### What does it say about education and training?

The following excerpts are from CMMC Version 1.02 | March 18, 2020

#### 2.3.5 CMMC Level 3
> Processes: managed
> Level 3 requires that an organization establish, maintain, and resource a plan demonstrating that management of activities for practice implementation. The plan may include information on missions, goals, project plans, resourcing, required training, and involvement of relevant stakeholders.

#### CMMC domains
> The CMMC model consists of 17 domains.

...[one of the domains is]
> Domain: Awareness and Training (AT)
> Capability:
> * Conduct security awareness activities
> * Conduct training

#### Awareness and Training (AT)
>Level 2
>AT.2.056 Ensure that managers, system administrators, and users of organizational systems are made aware of the security risks associated with their activities and of the applicable policies, standards, and procedures related to the security of those systems.
>At.2.057 Ensure that personnel are trained to carry out their assigned information security-related duties and responsibilities

>Level 3
>AT.3.058 Provide security awareness training on recognizing and reporting potential indicators of insider threat.

>Level 4
>AT.4.059 Provide awareness training focused on recognizing and responding to threats from social engineering, advanced persistent threat actors, breaches, and suspicious behaviors; update the training at least annually or when there are significant changes to the threat.
>AT.4.060 Include practical exercises in awareness training that are aligned with current threat scenarios and provide feedback to individuals involved in the training.



* IRAP/ISM
* ISMS (ISO 27001) - Information Security Management System
* BCMS (ISO 22301) - Business Continuity Management System
* IMS (Integrated Management system) ???
* PSPF/ISM
* APRA CPS 234
* ISO 14001 ???
* Essential 8 - I don't think there's anything there, though there may be in the other controls. I should look to see how far down training is.
* PSPF
* SOC 2/3
* GNGB
* SACSF
* VPDSF
* NSW CSP
* IS18
* NIST CSF
* C2M2??? Not a regulatory thing, but a cyber capability measurement assessment.
* CMMC - we don't deal with this, but it exists and has stuff on training. I think it's a NIST thing?
