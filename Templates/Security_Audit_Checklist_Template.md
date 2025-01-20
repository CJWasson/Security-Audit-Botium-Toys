# Security Audit Checklist Template

## General Information
- **Audit Name**: [Enter audit name]
- **Audit Date**: [Enter date]
- **Auditor(s)**: [List names]
- **Department/Business Unit**: [Enter department or business unit being audited]
- **Scope of Audit**: [Define the scope of this audit]

---

## Controls Assessment Checklist

| **Control**                     | **Yes** | **No** | **Explanation**                                                                                                                                 |
|---------------------------------|---------|--------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| **Least Privilege**             | [ ]     | [ ]    | Are employee privileges limited to reduce the risk of a breach?                                                                                |
| **Disaster Recovery Plans**     | [ ]     | [ ]    | Are disaster recovery plans in place to ensure business continuity?                                                                            |
| **Password Policies**           | [ ]     | [ ]    | Are there strong password requirements to secure employee accounts?                                                                            |
| **Separation of Duties**        | [ ]     | [ ]    | Are duties divided to reduce the possibility of fraud or critical data exposure?                                                               |
| **Firewall**                    | [ ]     | [ ]    | Does the firewall effectively block traffic based on predefined security rules?                                                                |
| **Intrusion Detection System**  | [ ]     | [ ]    | Is an IDS implemented to identify potential intrusions?                                                                                        |
| **Backups**                     | [ ]     | [ ]    | Are backups of critical data regularly created and securely stored?                                                                            |
| **Antivirus Software**          | [ ]     | [ ]    | Is antivirus software installed and regularly monitored?                                                                                       |
| **Monitoring for Legacy Systems** | [ ]     | [ ]    | Are legacy systems regularly monitored, maintained, and supported by clear procedures?                                                        |
| **Encryption**                  | [ ]     | [ ]    | Is encryption used to protect sensitive information?                                                                                           |
| **Password Management System**  | [ ]     | [ ]    | Is a password management system implemented to enhance security and productivity?                                                              |
| **Physical Security (Locks)**   | [ ]     | [ ]    | Are locks installed and functioning to secure offices, storefronts, and warehouses?                                                           |
| **CCTV Surveillance**           | [ ]     | [ ]    | Is CCTV installed and functioning to monitor physical locations?                                                                               |
| **Fire Detection/Prevention**   | [ ]     | [ ]    | Are fire detection and prevention systems in place and functioning properly?                                                                   |

---

## Compliance Assessment Checklist

### PCI DSS (Payment Card Industry Data Security Standard)

| **Best Practice**                                                                 | **Yes** | **No** | **Explanation**                                                                                          |
|-----------------------------------------------------------------------------------|---------|--------|----------------------------------------------------------------------------------------------------------|
| Only authorized users have access to customer credit card information.            | [ ]     | [ ]    | Are employee access privileges limited for sensitive data?                                               |
| Credit card information is stored securely in an encrypted environment.           | [ ]     | [ ]    | Is encryption in use for credit card data storage and transactions?                                      |
| Password management policies are in place to secure access.                       | [ ]     | [ ]    | Are strong password policies enforced?                                                                   |

---

### GDPR (General Data Protection Regulation)

| **Best Practice**                                                                 | **Yes** | **No** | **Explanation**                                                                                          |
|-----------------------------------------------------------------------------------|---------|--------|----------------------------------------------------------------------------------------------------------|
| E.U. customer data is encrypted to ensure privacy and security.                   | [ ]     | [ ]    | Is encryption used for securing customer data?                                                           |
| A notification plan exists for data breaches, within 72 hours of detection.       | [ ]     | [ ]    | Is there a documented and tested breach notification plan?                                               |
| Data is properly classified and inventoried to ensure efficient management.       | [ ]     | [ ]    | Are all data assets inventoried and classified?                                                          |

---

### SOC Type 1 and 2 (System and Organization Controls)

| **Best Practice**                                                                 | **Yes** | **No** | **Explanation**                                                                                          |
|-----------------------------------------------------------------------------------|---------|--------|----------------------------------------------------------------------------------------------------------|
| User access policies are established and implemented.                             | [ ]     | [ ]    | Are access policies like Least Privilege and Separation of Duties enforced?                               |
| Sensitive data (PII/SPII) is encrypted and access is limited to authorized users. | [ ]     | [ ]    | Is encryption used to ensure data confidentiality?                                                       |
| Data integrity measures ensure information is accurate and validated.             | [ ]     | [ ]    | Are there systems in place to maintain data integrity?                                                   |

---

## Action Plan

| **Finding**                      | **Impact (Low/Medium/High)** | **Recommended Actions**                         | **Assigned To**        | **Due Date**    |
|----------------------------------|-----------------------------|------------------------------------------------|-------------------------|-----------------|
| Example: Weak password policies  | High                        | Implement strong password policy requirements. | IT Security Team        | [Enter date]    |
| Example: No disaster recovery    | High                        | Develop and implement disaster recovery plans. | Operations Team         | [Enter date]    |

---

## Summary

### **Key Observations**
[Summarize key findings here.]

### **Recommendations**
[Provide overall recommendations for improving controls and compliance.]
