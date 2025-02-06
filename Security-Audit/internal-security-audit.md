# Controls and Compliance Assessment 

## Scenario

This is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

## Scope 

The scope is defined as the entire security program at Botium Toys. This means all assets need to be assessed alongside internal processes and procedures related to the implementation of controls and compliance best practices.

## Goals
Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to  improve Botium Toys’ security posture.

## Current assets
Assets managed by the IT Department include: 
* On-premises equipment for in-office business needs
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
* Internet access
* Internal network
* Data retention and storage
* Legacy system maintenance: end-of-life systems that require human monitoring 

## Risk assessment

### Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 

### Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

### Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

### Additional comments
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

### Control categories end types

Controls within cybersecurity are grouped into three main categories: 
1. Administrative/Managerial controls
2. Technical controls
3. Physical/Operational controls

Control types include, but are not limited to:
1. Preventative 
2. Corrective 
3. Detective 
4. Deterrent 

## Controls and compliance checklist
### Controls Assessment Checklist

Does Botium Toys currenly have this control in place? 

| Yes or No | Control | Explanation |
| :-------     |    :---:   | :---     |
| No | Least Privilige |The employees have access to customer data; privileges need to be limited to reduce the risk of a breach. |
| No | Disaster Recovery Plan |There is no plan for handling disaster. These need to be implemented to ensure business continuity. |
| No | Password policies | Employee password requirements are minimal which can put the identity management access at risk. |
| No | Separation of duties | Needs to be implemented to reduce the possibility of fraud/access to critical data. |
| Yes | Firewall | The existing  firewall blocks traffic based on an appropriately defined set of security rules. |
| No | IDS | This would help the IT team to identify possible intrusions by the threat actors. | 
| Yes | Antivirus | The antivirus software is active and regulary monitored by IT team. |
| No | Backups | The IT department needs to have backups of critical data, in the case of a breach, to ensure business continuity. |
| No | Password management system | There is no password management system currently in place, it should be implemented. |
| No | Encryption | This would protect confidentiality of data. |
| Yes | Locks| The organization have sufficient locks.|
| Yes | Closed-circuit television (CCTV) | It is working and functioning. |
| Yes | Fire detection/prevention |Botium Toys’ physical location has a functioning re detection and prevention system. |

### Compliance Checklist
Does Botium Toys currenly adhrere to this compliance best practice? 

* Payment Card Industry Data Security Standard (PCI DSS)

| Yes or No | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | Authorized users can access to customer's credit card. | At the moment, all employees have access to it which is a bad practice in the business.  |
| No | Credit card is stored in a secure environment. | It is not encrypted and violates the law and regulations. |
| No | Encryption is secured. | No, the encryption has not taken place yet. | 

* GDPR
  
| Yes/ No / ? | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | EU customers are kept secured. | The organization does not apply GDPR practice. Thus, it puts them at risk of being fined by the EU government. |
| Yes | Privacy policies are maintained properly.| According to the scenario, it has been enforced by the IT Team members and other staff. |

* System and Organizations Controls 

| Yes/ No / ? | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | User access policies are established | Employees have access to internally stored data which means the access policy has not been applied. |
| Yes | Data integrity is consistent, complete, accurate | Data integrity is in place. | 
| No | Data is available to authorized users | Currently, all the employees can access all the data. |

## Recommendations (optional)

After researching Botium Toys's security posture, the analysts agreed that the security practice is far from the expectation. It lacks of protection of confidentialiy of sensitive information. The following are:
1. Least privilege
2. Disaster recovery plan
3. Password policies
4. Encryption
5. Password management system

To address gaps in compliance, Botium needs to implement and establish the policies that can address the following above. Botium also needs to update its assets so the additional control can be identified as soon as possible to improve their security practice. 
