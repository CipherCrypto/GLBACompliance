# IT Risk Assessment Report

This report presents the findings from a thorough risk assessment of the organization's IT assets. It aims to identify vulnerabilities and security risks associated with the hardware, software, data assets, and connectivity infrastructure. Recommendations are provided to mitigate identified risks.

## Hardware Risks and Recommendations

### Computing Devices

- **Dell OptiPlex 7070 & HP EliteDesk 800 G4**
  - **Risk:** Outdated Windows 10 Pro version 1909 may contain unpatched vulnerabilities.
  - **Recommendation:** Upgrade to the latest Windows 10 version to ensure all security patches are applied.

- **Lenovo ThinkPad X1 Carbon**
  - **Risk:** VPN connectivity issues may indicate configuration vulnerabilities or outdated VPN client software.
  - **Recommendation:** Investigate and resolve VPN issues, ensuring the VPN client is updated to the latest version.

- **MacBook Pro 13"**
  - **Risk:** Battery health issues could lead to unexpected shutdowns, potentially disrupting secure operations.
  - **Recommendation:** Perform a battery health check and replace if necessary to ensure device reliability.

### Networking Equipment

- **Cisco ISR 4321 Router**
  - **Risk:** Router operating under increased traffic load may lead to performance bottlenecks and potential security risks.
  - **Recommendation:** Assess current and projected traffic patterns and upgrade router hardware or optimize configurations as needed.

## Software Risks and Recommendations

### Operating Systems

- **General Risk:** Running outdated operating systems or software versions can expose systems to known vulnerabilities.
- **Recommendation:** Implement a regular update and patch management policy to keep all operating systems and software up-to-date.

### Applications

- **Microsoft Office 365 & Adobe Creative Cloud**
  - **Risk:** Accounts without Multi-Factor Authentication (MFA) are more susceptible to compromise.
  - **Recommendation:** Enforce MFA for all user accounts to enhance security.

## Data Assets Risks and Recommendations

### Structured and Unstructured Data

- **HR_System Database & Project_Plans**
  - **Risk:** Insufficient data retention and deletion policies could lead to data storage of obsolete, sensitive information, increasing the risk of data breaches.
  - **Recommendation:** Develop and implement a data retention policy that includes regular reviews and secure deletion practices for outdated data.

## Connectivity Assets Risks and Recommendations

### Network Topology Documentation

- **Risk:** Inadequate version control and access management for sensitive network documentation can lead to unauthorized access and potential security breaches.
- **Recommendation:** Strengthen access controls and implement a secure version control system for network documentation.

### Virtual Private Networks (VPNs)

- **Risk:** Inconsistent application of Multi-Factor Authentication (MFA) across all remote connections increases the risk of unauthorized access.
- **Recommendation:** Ensure MFA is consistently enforced for all VPN connections to enhance remote access security.

### Cloud Services

- **AWS Account**
  - **Risk:** Overly permissive IAM roles and policies can lead to unauthorized access and potential data breaches.
  - **Recommendation:** Conduct regular audits of IAM roles and policies to ensure they adhere to the principle of least privilege.

### Conclusion
This detailed risk assessment has highlighted several key areas where the organization's IT assets are vulnerable to security risks. Addressing these through the recommended actions will significantly improve the organization's cybersecurity posture and resilience against potential threats.
