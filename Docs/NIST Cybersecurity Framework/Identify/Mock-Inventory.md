# IT Asset Management Inventory

## Hardware Inventory
- **Desktops**
  - **Dell OptiPlex 7070**
    - **Model:** D07U
    - **Serial:** 5JKS92D
    - **Location:** Floor 3, Desk 14
    - **User:** John Doe
    - **Configuration:** Intel Core i7, 16GB RAM, 512GB SSD
    - **Installation Date:** Jan 10, 2020
    - **Warranty Expiry:** Jan 10, 2023
    - **Security Features:** TPM 2.0 for BitLocker encryption
    - **Comments:** Scheduled for software update in Q2

  - **HP EliteDesk 800 G4**
    - **Model:** 4KW48ET
    - **Serial:** 8HCKVZ1
    - **Location:** Floor 2, Desk 8
    - **User:** Jane Smith
    - **Configuration:** Intel Core i5, 8GB RAM, 256GB SSD
    - **Installation Date:** Mar 15, 2019
    - **Warranty Expiry:** Mar 15, 2022
    - **Security Features:** BIOS password set, Secure Boot enabled
    - **Comments:** Needs SSD upgrade due to performance issues

- **Laptops**
  - **Lenovo ThinkPad X1 Carbon**
    - **Model:** 20QD0032US
    - **Serial:** PF0KXFAT
    - **Location:** Mobile, frequently used in Conference Room B
    - **User:** Alice Johnson
    - **Configuration:** Intel Core i7, 16GB RAM, 1TB SSD
    - **Installation Date:** Aug 22, 2021
    - **Warranty Expiry:** Aug 22, 2024
    - **Security Features:** Disk encryption enabled, fingerprint reader
    - **Comments:** Review VPN connectivity issues reported last week

  - **MacBook Pro 13"**
    - **Model:** A2251
    - **Serial:** C02ZD05MLVC8
    - **Location:** Mobile, often used for client presentations
    - **User:** Bob Brown
    - **Configuration:** Apple M1, 8GB RAM, 512GB SSD
    - **Installation Date:** Nov 5, 2020
    - **Warranty Expiry:** Nov 5, 2023
    - **Security Features:** FileVault disk encryption active, Touch ID enabled
    - **Comments:** Monitor battery health, user reports rapid drain

#### Networking Equipment

- **Routers**
  - **Cisco ISR 4321**
    - **Model:** ISR4321/K9
    - **Serial:** FTX2142Q1GH
    - **Location:** Server Room, Rack 4
    - **Configuration:** 2x Gigabit Ethernet ports, 4GB RAM, 4GB Flash
    - **Installation Date:** June 12, 2018
    - **Warranty Expiry:** June 12, 2021
    - **Security Features:** ACLs in place, IOS Firewall enabled
    - **Comments:** Evaluate upgrade for increased traffic load

#### Peripherals and Accessories

- **Printers**
  - **HP LaserJet Pro M404dn**
    - **Model:** W1A53A
    - **Serial:** VNC8N12345
    - **Location:** Floor 1, Print Station 3
    - **Configuration:** Duplex printing, Ethernet connected
    - **Installation Date:** Sep 7, 2019
    - **Warranty Expiry:** Sep 7, 2022
    - **Security Features:** Firmware updated to latest version for vulnerability patches
    - **Comments:** High usage, monitor for maintenance needs

### Software Inventory

#### Operating Systems

- **Desktops**
  - **OS:** Windows 10 Pro
  - **Version:** 1909
  - **Patch Level:** December 2021
  - **Security Features:** BitLocker encryption, Windows Defender enabled
  - **Comments:** Plan upgrade to Windows 10 version 21H1

- **Laptops**
  - **OS:** macOS Catalina
  - **Version:** 10.15.7
  - **Patch Level:** December 2021
  - **Security Features:** FileVault encryption, Gatekeeper enabled
  - **Comments:** Monitor end-of-support dates for OS upgrade planning

#### Applications

- **Microsoft Office 365**
  -

 **Version:** 2021
  - **License Key:** XXXXX-XXXXX-XXXXX-XXXXX-XXXXX
  - **Users:** All company employees
  - **Security Features:** Multi-Factor Authentication enabled for all users
  - **Comments:** Review usage analytics for potential license optimization

- **Adobe Creative Cloud**
  - **Version:** 5.4
  - **License Key:** ZZZZZ-ZZZZZ-ZZZZZ-ZZZZZ-ZZZZZ
  - **Users:** Design Team (12 licenses)
  - **Security Features:** Regular software updates for security patches
  - **Comments:** Assess additional needs for upcoming graphic projects

#### Databases

- **Oracle Database**
  - **Version:** 19c
  - **Location:** IBM Power System S922, Data Center
  - **Hosted Databases:** HR_System, Inventory_Management
  - **Security Features:** Encrypted connections, access controls based on roles
  - **Comments:** Plan for 19c end-of-life and potential migration strategies

### Data Assets

#### Structured Data

- **HR_System Database**
  - **Location:** IBM Power System S922
  - **Sensitivity:** Confidential
  - **Access Controls:** Limited to HR department, encrypted backups
  - **Comments:** Regular audits for data accuracy and compliance with data protection regulations

#### Unstructured Data

- **Project_Plans**
  - **Location:** Google Drive, Project Management folder
  - **Owner:** Project Management Office
  - **Sensitivity:** Confidential
  - **Access Controls:** Two-factor authentication for access, sharing restricted to project team members
  - **Comments:** Implement regular review cycles for document retention and deletion policy

### Connectivity Assets

#### Network Topology Documentation

- **Details:** Comprehensive diagrams updated quarterly, stored in SharePoint, IT Documentation folder
- **Access Controls:** Accessible by IT department and senior management
- **Security Features:** Sensitive information redacted from general access versions
- **Comments:** Ensure version control is strictly adhered to, with historical versions archived

#### Virtual Private Networks (VPNs)

- **Cisco AnyConnect Secure Mobility Client**
  - **Configuration:** AES-256 encryption, split tunneling disabled
  - **Users:** All remote employees
  - **Security Features:** Mandatory Multi-Factor Authentication
  - **Comments:** Regularly review user access logs and session durations for anomalies

#### Cloud Services

- **AWS Account**
  - **Account ID:** 1234-5678-9012
  - **Services Utilized:** EC2, S3, RDS, Lambda
  - **IAM Roles:** Defined for Admin, Developer, Auditor with least privilege access
  - **Security Features:** All data in S3 buckets encrypted at rest, CloudTrail for audit logs
  - **Comments:** Conduct a bi-annual review of all IAM roles and policies for necessary adjustments
