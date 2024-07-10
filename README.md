# Botium_Toys_Internal_Security_Audit
# Introduction
An internal security audit was conducted for Botium Toys, a fictional toy company, as a component of my cybersecurity portfolio and the Google Cybersecurity Professional Certificate on Coursera, within the "Play It Safe: Manage Security Risks" course.

The primary objective was to evaluate Botium Toys' cybersecurity framework, ensuring it aligns with industry standards and best practices. This audit aimed to identify and address high-risk vulnerabilities, offering recommendations for resolutions. Additionally, it included devising a strategic plan to enhance the company's overall security posture. The audit team was responsible for documenting their findings, proposing remediation efforts, and effectively communicating with relevant stakeholders.

# Scenerio
Botium Toys, a small U.S. business with a single location serving as its main office, storefront, and warehouse, has seen significant growth in its online presence, attracting customers domestically and internationally. This expansion has increased the pressure on their IT department to support global operations.

Concerned about maintaining compliance and business operations amid this growth, the IT manager has decided to conduct an internal IT audit. She aims to secure the company's infrastructure, identify and mitigate potential risks, and ensure compliance with online payment processing and E.U. regulations.

To initiate this process, the IT manager has implemented the NIST Cybersecurity Framework (NIST CSF), defined the audit scope and goals, cataloged IT-managed assets, and completed a risk assessment. The audit's objective is to evaluate the risks and potential fines the company may face due to its current security posture.

My task is to review the IT manager’s scope, goals, and risk assessment report, and then perform an internal audit by completing a controls and compliance checklist.


Botium Toys, a small U.S. business with a single location serving as its main office, storefront, and warehouse, has seen significant growth in its online presence, attracting customers domestically and internationally. This expansion has increased the pressure on their IT department to support global operations.

Concerned about maintaining compliance and business operations amid this growth, the IT manager has decided to conduct an internal IT audit. She aims to secure the company's infrastructure, identify and mitigate potential risks, and ensure compliance with online payment processing and E.U. regulations.

To initiate this process, the IT manager has implemented the NIST Cybersecurity Framework (NIST CSF), defined the audit scope and goals, cataloged IT-managed assets, and completed a risk assessment. The audit's objective is to evaluate the risks and potential fines the company may face due to its current security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report, and then perform an internal audit by completing a controls and compliance checklist.


Botium Toys, a small U.S. business with a single location serving as its main office, storefront, and warehouse, has seen significant growth in its online presence, attracting customers domestically and internationally. This expansion has increased the pressure on their IT department to support global operations.

Concerned about maintaining compliance and business operations amid this growth, the IT manager has decided to conduct an internal IT audit. She aims to secure the company's infrastructure, identify and mitigate potential risks, and ensure compliance with online payment processing and E.U. regulations.

To initiate this process, the IT manager has implemented the NIST Cybersecurity Framework (NIST CSF), defined the audit scope and goals, cataloged IT-managed assets, and completed a risk assessment. The audit's objective is to evaluate the risks and potential fines the company may face due to its current security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report, and then perform an internal audit by completing a controls and compliance checklist.

The goals for Botium Toys’ internal IT audit are:

- To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)
- Establish a better process for their systems to ensure they are compliant
- Fortify system controls
- Implement the concept of least permissions when it comes to user credential management
- Establish their policies and procedures, which includes their playbooks
- Ensure they are meeting compliance requirements

# Internal Security Audit Workflow
This process can be broken down into two parts:
## Part 1
1. Analyze the audit scope, goals, and risk assessment
2. Conduct the Audit
   - Complete the Controls Assessment by selecting the controls that need to be implemented.         As well as rate each selected control on priority.
   - Complete the Compliance Checklist explaining why selected compliance regulations and            standards need to be adhered to.
  
## Part 2
1. Review findings and deliverables completed in Part 1. By documenting findingd, summarizing      recommendations clearly and concisely.
2. Present finding and recommnedations to stakeholders in a clear and concise format.

# Controls Assessment
## Current assets
Assets managed by the IT Department include:
● On-premises equipment for in-office business needs
● Employee equipment: end-user devices (desktops/laptops, smartphones),
remote workstations, headsets, cables, keyboards, mice, docking stations,
surveillance cameras, etc.
● Storefront products available for retail sale on site and online; stored in the
company’s adjoining warehouse
● Management of systems, software, and services: accounting,
telecommunication, database, security, ecommerce, and inventory
management
● Internet access
● Internal network
● Data retention and storage
● Legacy system maintenance: end-of-life systems that require human
  monitoring

### Controls Assessmet CheckList
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Least Privilege | Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs | X | High |
| Disaster recovery plans | Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration | X | High |
| Password policies | Preventative; establish complex password requirements to improve security/reduce likelihood of account compromise | X | High |
| Separation of duties | Preventative; ensure no one has so much access that they can abuse the system for personal gain | X | High |
| Firewall | Preventative; firewalls ***are already in place*** to filter unwanted/malicious traffic from entering internal network | NA | NA |
| Intrusion Detection System (IDS) | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | X | High |
| Backups | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | X | High |
| Antivirus (AV) software | Corrective; **are in place already** detect and quarantine known threats | NA | NA |
| Manual monitoring, maintenance, and intervention | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | X | High |
| Encryption | Deterrent; makes confidential information/data more secure (e.g., website payment transactions) | X | High |
| Password management system | Corrective; password recovery, reset, lock out notifications | X | High |
| Locks | Preventative; **are in place already** physical and digital assets are more secure | N/A | N/A |
| Closed-circuit television (CCTV) surveillance | Preventative/detective;**are already in place** can reduce risk of certain events; can be used after event for investigation | N/A | N/A |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative; **are in place already** detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc. | N/A | N/A |


| Access control policies | Preventative; increase confidentiality and integrity of data | X | High |
| Account management policies | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees | X | High |



### Compliance Checklist
| Compliance Regulation | explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Only Authorized users have access to customers credit card info | Preventative; reduce attack surface area | X | High |
| Credit Card information is stored, accepted, processed, and transmitted internally, in a secure environment | Preventative; keeping sensitive information safe and accessible to authorized staff | X | High |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data | Preventative; encryption ensures sensitive information is converted into secure format that can only be read by authorized parties | X | High |
| Adopt secure password management policies | Preventative; prevent security incidents by ensuring that passwords are strong, regulary updated | X | High |
| E.U customers' data is kept private/secured | Preventative; focuses on implementing practices and controls to prevent unauthorized access and ensure the privacy and security of E.U customer data | X | High |
| There is a plan in place to notifiy E.U customer within 72 hours if their data is compromised/there is a breach | Preventative; **are already in place** | NA | NA |
| Ensure data is properly classifies and inventoried | Preventative; helps to identify the sensitive and value of data, enabling appropriate security controls to be applied and ensuring data is handled accordingly | X | High |
| Enforce privacy policies, procedures, and processes to properly document and maintain data | Preventative; **already in place** | NA | NA |
| User access policies are established | Preventative; prevent unauthorized access by defining who can access what information | X | High |
| Sensitive data (PII/SPII) is confidential/private | Preventative; ensure sensitive data is kept confidential and private | X | High |
| Data integrity ensures the data is consistent, complete, accurate, and has been validated | Preventative; **are already in place** ensures data remains reliable and unaltered, preventing issues related to data corruption | NA | NA |
| Data is available to individuals authorized to access it | Preventative; ensure data availability to authorized staff prevents access issues and supports continuous business operations | X | High |

# Stakeholder memorandum <a name="stakeholder-memo">

TO: IT Manager, Stakeholders

FROM: Maya Campbell\
DATE: 07/10/2024\
SUBJECT: Internal IT Audit Findings and Recommendations

Dear Colleagues,

Kindly examin the details regarding the Botium Toys internal audit, which covers the scope, objectives, key findings, overview, and recommendations.

**Scope:**
- The following systems are in scope: firewalls, antivirus software, itrusion detection system, security information and event managemnt (SIEM) tool.  The systems will be evaluated for:
     - Existing user permissions
     - Implemented controls
     - Operational procedures and protocols
 
- Verification that current user permissions, controls, procedures, and protocols adhere to GDPR, PCI DSS, and other compliance standards
  
- Confirmation of the comprehensive accounting for current technology and assets, encompassing both hardware and system access

**Goals:**

- Adhere to the NIST CSF.

- Establish a better process for their systems to ensure they are compliant

- Fortify system controls

- Implement the concept of least permissions when it comes to user credential management

- Establish their policies and procedures, which includes their playbooks

  **Critical Findings** (must be addressed immediately):
  Multiple controls need to be developed amd implemented to meet the audit goals, including:
  - Principle of Least Privilage and Separation of duties
  - Disaster Recovery Plans
  - Password Policies& Password Management System
  - Intrusion Detection System
  - Backups
  - Manual Monitoring, Maintenance, and Intervention for Legacy Systems
  - Encryption
  Multiple compliance regulations need to nbe adhered to meet GDPR, PCI DSS & System and Organization Controls :
**Payemnt Card Industry Data Securty Standard (PCI DSS)**
  - Only authorized users have access to customers' credit card information
  - Credit card information stored, accepted, processed, and transmitted internally, in a secure environment.
  - Implement data encryption procedures to better secure credit card transactions touchpoints and data
  - Adopt secure password managment policies
**General Data Protection Regulation (GDPR)**
  - E.U. cutomers' data is kept private/secured
  - Ensure data is properly classified and inventoried
**Systems and Organizations Controls (SOC type 1,SOC type 2)**
  - User access policies and established
  - Sensitive data (PII/SPII) is confidential
  - Data is available to indivduals authorized to access it
 
**Summary/Recommendations:**
It is advised to promptly address critical findings related to PCI and GDPR compliance at Botium Toys, especially as the company expands its online payment acceptance and extends services to customers globally, including those in the European Union. Aligning with SOC1 and SOC2 guidelines on user access policies is crucial to achieving the audit's goal of implementing least privilege principles and establishing compliant policies and procedures.

Implementing disaster recovery plans and backups is recommended to ensure business continuity in various scenarios, such as physical disasters like fires, or worst-case scenarios involving cyberattacks or technical disruptions. Including fire detection and prevention systems should be considered to enhance physical security measures.

Integrating IDS and AV software into current systems will enhance intrusion detection capabilities and help mitigate potential risks, particularly concerning legacy systems that require manual monitoring and intervention.

# Conclusion <a name="conclusion">
This concludes my mock security audit writeup. I trust you found it informative and beneficial. If there are any suggestions or constructive feedback to enhance and expand upon it further, please feel free to let me know. I'm here to assist with any additional improvements or clarifications you may need.

**Self-Evaluation**: I believe I did well determining what controls are top priority and need to be implemented immediately in reducing risk and why Botium Toys would need to comply to the regulations and standards I initially picked on my first try.  I enjoyed that this challenged my thinking and tested what I have learned in my studies and hands-on learning so far.

 
