# security-audit
## Botium Toys: Scope, goals, and risk assessment report

### Scope and goals of the audit
_Scope:_ The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. You will need to review the assets Botium Toys has and the controls and compliance practices they have in place.
_Goals:_ Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented to  improve Botium Toys’ security posture.
### Current assets
Assets managed by the IT Department include: 
- On-premises equipment for in-office business needs  
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring 
  ## Risk assessment
  ## Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 
### Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.
### Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.
### Additional comments
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details: 

- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
- Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database. 
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department. 
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data. 
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters). 
- There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.


### Controls and compliance checklist

To complete the controls assessment checklist, I referred to the information provided in the scope, goals, and risk assessment report. Then, ro evaluate the controls assessment I did a checklist and selected “yes” or “no” to answer the question: Does Botium Toys currently have this control in place? 


Controls assessment checklist

  | Yes  | No   | Control                                                |
|------|------|--------------------------------------------------------|
| ☐    | ☑    | Least Privilege                                         |
| ☐    | ☑    | Disaster Recovery Plans                                 |
| ☐    | ☑    | Password Policies                                       |
| ☐    | ☑    | Separation of Duties                                    |
| ☑    | ☐    | Firewall                                                |
| ☐    | ☑    | Intrusion Detection System (IDS)                        |
| ☐    | ☑    | Backups                                                 |
| ☑    | ☐    | Antivirus Software                                      |
| ☐    | ☑    | Manual Monitoring, Maintenance, and Intervention for Legacy Systems |
| ☐    | ☑    | Encryption                                              |
| ☐    | ☑    | Password Management System                              |
| ☑    | ☐    | Locks (Offices, Storefront, Warehouse)                  |
| ☑    | ☐    | Closed-Circuit Television (CCTV) Surveillance           |
| ☑    | ☐    | Fire Detection/Prevention (Fire Alarm, Sprinkler System, etc.) |



To complete the compliance checklist, I referred to the information provided in the scope, goals, and risk assessment report.
Compliance checklist

### Payment Card Industry Data Security Standard (PCI DSS)
| Yes  | No   | Best Practice                                           | Explanation                                                                                       |
|------|------|---------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| ☐    | ☑    | Only authorized users have access to customers’ credit card information. | Currently, all employees have unrestricted access to the company’s internal data, including sensitive customer information. |
| ☐    | ☑    | Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. | Credit card information is not encrypted, and all employees can access it, exposing customers' financial data to potential risks. |
| ☐    | ☑    | Implement data encryption procedures to better secure credit card transaction touchpoints and data. | The company does not currently employ encryption techniques to safeguard the confidentiality of customers’ financial information. |
| ☐    | ☑    | Adopt secure password management policies.             | The existing password policies are minimal, and there is no password management system in place, leading to potential security vulnerabilities. |

To complete the PCI DSS compliance checklist, I referred to the information provided in the scope, goals, and risk assessment report. And compared it to most recent PCI DSS best practice.

### Compliance checklist
### General Data Protection Regulation (GDPR)

| Yes  | No   | Best Practice                                           | Explanation                                                                                       |
|------|------|---------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| ☐    | ☑    | E.U. customers’ data is kept private/secured.           | The company currently lacks sufficient measures to ensure that E.U. customers' data is adequately protected and secured. |
| ☑    | ☐    | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | A notification plan is established to inform E.U. customers within 72 hours in the event of a data breach, meeting GDPR requirements. |
| ☐    | ☑    | Ensure data is properly classified and inventoried.     | Data is inventored but not consistently classified, leading to challenges in managing and securing sensitive information effectively. |
| ☑    | ☐    | Enforce privacy policies, procedures, and processes to properly document and maintain data. | Privacy policies and procedures are enforced, ensuring that data is documented and maintained in accordance with regulatory standards. |

To complete the GDPR compliance checklist, I referred to the information provided in the scope, goals, and risk assessment report. And refered it to GDPR best practice.




### System and Organizations Controls (SOC type 1, SOC type 2) 
### Best Practices Assessment

| Yes  | No   | Best Practice                                           | Explanation                                                                                       |
|------|------|---------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| ☐    | ☑    | User access policies are established.                   | User access policies are not fully established, leading to potential unauthorized access to sensitive systems and data. |
| ☐    | ☑    | Sensitive data (PII/SPII) is confidential/private.      | There are insufficient controls in place to ensure that sensitive data, such as PII/SPII, is kept confidential and secure. |
| ☑    | ☐    | Data integrity ensures the data is consistent, complete, accurate, and has been validated. | Data integrity is maintained, ensuring that data is consistent, complete, accurate, and validated across the organization. |
| ☐    | ☑    | Data is available to individuals authorized to access it. | Data availability is currently too broad, allowing both authorized and non-authorized employees access. Access should be restricted on a need-to-know basis. |

To complete the (SOC type 1, SOC type 2) compliance checklist, I referred to the information provided in the scope, goals, and risk assessment report. And refered it to the most recent (SOC type 1, SOC type 2) best practices.

## Recommendations
 In this section, I will provide my recommendations, related to controls and/or compliance needs, that your IT manager could communicate to stakeholders to reduce the risks to assets and improve Botium Toys’ security posture.
Recommendations: 

### Risk Description
Botium Toys currently faces significant risks due to inadequate asset management, insufficient controls, and non-compliance with U.S. and international regulations and standards. This exposes the organization to potential financial penalties, loss of customer trust, and business continuity risks.
### Control Best Practices
The first function of the NIST Cybersecurity Framework (CSF) is Identify. To mitigate the identified risks, Botium Toys should allocate resources to properly identify and classify all assets. This includes hardware, software, data, and personnel. By doing so, the company can effectively manage these assets and assess the impact of their loss on business continuity.
## Security Assessment and Recommendations for Botium Toys

### Risk Description
Currently, Botium Toys is facing significant security risks due to inadequate management of assets, lack of proper controls, and potential non-compliance with U.S. and international regulations and standards. These gaps could expose the company to data breaches, financial penalties, and a loss of customer trust.

### Control Best Practices
The **NIST Cybersecurity Framework (CSF)** emphasizes the importance of the Identify function as the first step towards securing an organization. Botium Toys must allocate resources to:

- **Identify and classify assets**: This includes evaluating the business continuity impact of asset loss.
- **Implement least privilege access**: Ensure that only authorized users have access to critical data, such as customers' credit card information and personally identifiable information (PII).
- **Adopt encryption methods**: Secure credit card transactions and data storage by implementing robust encryption protocols.
- **Establish strong password policies**: Update password requirements to align with modern standards and enforce them through a centralized password management system.

### Risk Score
- **Risk Score**: 8/10 (High)
  - The high score reflects the current lack of controls and compliance with best practices, which poses a serious threat to Botium Toys' assets and overall security posture.

### Specific Recommendations

1. **Access Control and Data Security**
   - **Implement Least Privilege Access**: Ensure only authorized personnel can access sensitive data, particularly cardholder data and PII/SPII.
   - **Encryption**: Introduce encryption for all credit card information that is accepted, processed, transmitted, and stored internally.

2. **Compliance Requirements**
   - **PCI DSS Compliance**: 
     - Implement controls to ensure that credit card data is processed in a secure environment.
     - Encrypt credit card transaction data at all touchpoints.
   - **GDPR Compliance**:
     - Maintain the privacy and security of E.U. customers' data.
     - Enforce robust privacy policies, procedures, and processes.
   - **SOC Compliance**:
     - Establish user access policies.
     - Ensure the confidentiality of sensitive data, including PII/SPII.

3. **Infrastructure and Monitoring**
   - **Intrusion Detection System (IDS)**: Deploy an IDS to monitor network traffic for suspicious activity and potential threats.
   - **Disaster Recovery Planning**: Develop and implement a comprehensive disaster recovery plan, including regular backups of critical data.
   - **Legacy Systems Maintenance**: Schedule regular monitoring, maintenance, and intervention for legacy systems to prevent vulnerabilities.

4. **Password Management**
   - **Update Password Policies**: Align with current standards by requiring complex passwords (at least eight characters, including letters, numbers, and special characters).
   - **Centralized Password Management**: Implement a system that enforces password policies and reduces the need for manual password recovery processes.

### Additional Comments
While Botium Toys has implemented some security measures, such as firewalls and antivirus software, there are critical areas that require immediate attention. Addressing these vulnerabilities will significantly improve the company’s security posture and reduce the risks of data breaches and non-compliance penalties.

---

**Disclaimer**: This document provides an overview of recommendations based on an initial security assessment. It is advised that Botium Toys conducts a more thorough audit to tailor these recommendations to their specific operational needs.

The current risk score is 8 out of 10, indicating a fairly high level of risk due to the lack of controls and adherence to compliance best practices. Implementing the above recommendations will help reduce this score and improve Botium Toys' overall security posture.
Additional Comments
While Botium Toys has made some progress in securing its IT infrastructure, significant gaps remain, particularly in encryption, access control, and compliance. Addressing these gaps should be a priority to reduce the potential impact of asset loss, fines from governing bodies, and damage to the company’s reputation and clients trust.
 Failure to take timely action on these recommendations may result in a costly audit and increased risk of non-compliance penalties or security breaches.

