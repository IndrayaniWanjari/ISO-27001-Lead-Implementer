# Annex A – A.8 Technological Controls (Hardware-Oriented) (ISO/IEC 27001:2022)

> This section covers technological controls primarily related to hardware, infrastructure, and physical technology configurations.

## Table of Contents
- [A.8.1 User Endpoint Devices](#a81-user-endpoint-devices)
- [A.8.2 Privileged Access Rights](#a82-privileged-access-rights)
- [A.8.3 Information Access Restriction](#a83-information-access-restriction)
- [A.8.4 Access to Source Code](#a84-access-to-source-code)
- [A.8.5 Secure Authentication](#a85-secure-authentication)
- [A.8.6 Capacity Management](#a86-capacity-management)
- [A.8.7 Protection against Malware](#a87-protection-against-malware)
- [A.8.8 Management of Technical Vulnerabilities](#a88-management-of-technical-vulnerabilities)
- [A.8.9 Configuration Management](#a89-configuration-management)
- [A.8.10 Information Deletion](#a810-information-deletion)
- [A.8.11 Data Masking](#a811-data-masking)
- [A.8.12 Data Leakage Prevention](#a812-data-leakage-prevention)
- [A.8.13 Information Backup](#a813-information-backup)
- [A.8.14 Redundancy of Information Processing Facilities](#a814-redundancy-of-information-processing-facilities)
- [A.8.15 Logging](#a815-logging)
- [A.8.16 Monitoring Activities](#a816-monitoring-activities)
- [A.8.17 Clock Synchronization](#a817-clock-synchronization)
- [A.8.18 Use of Privileged Utility Programs](#a818-use-of-privileged-utility-programs)
- [A.8.19 Installation of Software on Operational Systems](#a819-installation-of-software-on-operational-systems)
- [A.8.20 Networks Security](#a820-networks-security)
- [A.8.21 Security of Network Services](#a821-security-of-network-services)
- [A.8.22 Segregation of Networks](#a822-segregation-of-networks)
- [A.8.23 Web Filtering](#a823-web-filtering)
- [A.8.24 Use of Cryptography](#a824-use-of-cryptography)
- [A.8.25 Secure Development Life Cycle](#a825-secure-development-life-cycle)
- [A.8.26 Application Security Requirements](#a826-application-security-requirements)
- [A.8.27 Secure System Architecture and Engineering Principles](#a827-secure-system-architecture-and-engineering-principles)
- [A.8.28 Secure Coding](#a828-secure-coding)
- [A.8.29 Security Testing in Development and Acceptance](#a829-security-testing-in-development-and-acceptance)
- [A.8.30 Outsourced Development](#a830-outsourced-development)
- [A.8.31 Separation of Development, Test and Production Environments](#a831-separation-of-development-test-and-production-environments)
- [A.8.32 Change Management](#a832-change-management)
- [A.8.33 Test Information](#a833-test-information)
- [A.8.34 Protection of Information Systems during Audit Testing](#a834-protection-of-information-systems-during-audit-testing)

## A.8.1 User Endpoint Devices

**Description**  
Protect endpoint devices such as laptops, mobile devices, and desktops from security threats.

**Technology**  
Endpoint protection platforms (EPP), mobile device management (MDM), disk encryption.

**Organization/processes**  
Enforce baseline configurations, patching schedules, and device encryption policies.

**People**  
Train users on secure device handling and reporting lost/stolen devices.

**Documentation**  
* **Mandatory:** Endpoint Device Security Policy (if control applicable)  
* **Optional:** Device Inventory Logs; Encryption Key Management Procedure  


## A.8.2 Privileged Access Rights

**Description**  
Restrict and control privileged accounts to minimize misuse risk.

**Technology**  
Privileged access management (PAM) tools, multi-factor authentication.

**Organization/processes**  
Enforce least privilege, require approval for privileged access, review access regularly.

**People**  
Train administrators on secure privileged account usage.

**Documentation**  
* **Mandatory:** Privileged Access Control Procedure (if control applicable)  
* **Optional:** Privileged Account Review Logs  

## A.8.3 Information Access Restriction

**Description**  
Restrict access to information and system functions based on business requirements.

**Technology**  
Role-based access control (RBAC), ACLs.

**Organization/processes**  
Assign access based on need-to-know, review periodically.

**People**  
Educate staff on data classification and access protocols.

**Documentation**  
* **Mandatory:** Access Control Policy (if control applicable)  
* **Optional:** Access Request & Approval Records  


## A.8.4 Access to Source Code

**Description**  
Restrict access to source code to authorized personnel.

**Technology**  
Version control systems with access restrictions, code review tools.

**Organization/processes**  
Enforce code repository permissions, monitor changes.

**People**  
Train developers on secure code handling.

**Documentation**  
* **Mandatory:** Source Code Access Procedure (if control applicable)  
* **Optional:** Code Repository Access Logs  


## A.8.5 Secure Authentication

**Description**  
Implement secure authentication methods for system access.

**Technology**  
MFA, password managers, biometric authentication.

**Organization/processes**  
Define password policies, enforce MFA, monitor authentication attempts.

**People**  
Train users on secure authentication practices.

**Documentation**  
* **Mandatory:** Authentication Policy (if control applicable)  
* **Optional:** MFA Enrollment Records  


## A.8.6 Capacity Management

**Description**  
Ensure systems have sufficient capacity to meet performance and availability requirements.

**Technology**  
Monitoring tools, capacity planning software.

**Organization/processes**  
Regularly assess system capacity and plan for growth.

**People**  
Train IT staff on capacity planning methodologies.

**Documentation**  
* **Mandatory:** Capacity Management Plan (if control applicable)  
* **Optional:** Capacity Reports  


## A.8.7 Protection against Malware

**Description**  
Implement controls to detect and prevent malware infections.

**Technology**  
Anti-malware software, endpoint protection platforms.

**Organization/processes**  
Schedule regular scans, update definitions.

**People**  
Educate users on safe computing practices.

**Documentation**  
* **Mandatory:** Anti-Malware Policy (if control applicable)  
* **Optional:** Malware Incident Logs  


## A.8.8 Management of Technical Vulnerabilities

**Description**  
Identify and mitigate vulnerabilities in a timely manner.

**Technology**  
Vulnerability scanners, patch management systems.

**Organization/processes**  
Schedule regular scans, prioritize remediation.

**People**  
Train staff on vulnerability management processes.

**Documentation**  
* **Mandatory:** Vulnerability Management Procedure (if control applicable)  
* **Optional:** Scan Reports  


## A.8.9 Configuration Management

**Description**  
Establish and maintain secure configurations for hardware, software, and systems.

**Technology**  
Configuration management databases (CMDB), automated configuration tools.

**Organization/processes**  
Document baseline configurations, monitor deviations.

**People**  
Train staff on secure configuration practices.

**Documentation**  
* **Mandatory:** Configuration Management Policy (if control applicable)  
* **Optional:** Configuration Baseline Documents  


## A.8.10 Information Deletion

**Description**  
Ensure secure deletion of information when no longer needed.

**Technology**  
Data wiping tools, secure erase utilities.

**Organization/processes**  
Define deletion processes for different media types.

**People**  
Train staff on secure deletion practices.

**Documentation**  
* **Mandatory:** Information Deletion Procedure (if control applicable)  
* **Optional:** Deletion Logs  


## A.8.11 Data Masking

**Description**  
Mask sensitive data to prevent unauthorized disclosure.

**Technology**  
Data masking software, tokenization tools.

**Organization/processes**  
Define masking rules and apply them consistently.

**People**  
Train developers and analysts on masking requirements.

**Documentation**  
* **Mandatory:** Data Masking Policy (if control applicable)  
* **Optional:** Masking Implementation Logs  


## A.8.12 Data Leakage Prevention

**Description**  
Prevent unauthorized transfer of sensitive data.

**Technology**  
DLP software, network monitoring tools.

**Organization/processes**  
Define DLP rules, monitor alerts.

**People**  
Train staff on data protection responsibilities.

**Documentation**  
* **Mandatory:** Data Leakage Prevention Policy (if control applicable)  
* **Optional:** DLP Incident Logs  


## A.8.13 Information Backup

**Description**  
Backup information to ensure availability and integrity.

**Technology**  
Backup software, offsite/cloud backups.

**Organization/processes**  
Schedule regular backups, test restorations.

**People**  
Train staff on backup policies.

**Documentation**  
* **Mandatory:** Backup Policy (if control applicable)  
* **Optional:** Backup Schedules; Restoration Test Logs  


## A.8.14 Redundancy of Information Processing Facilities

**Description**  
Implement redundancy to maintain availability in case of failure.

**Technology**  
Failover systems, load balancers.

**Organization/processes**  
Plan and test redundancy mechanisms.

**People**  
Train staff on failover procedures.

**Documentation**  
* **Mandatory:** Redundancy Plan (if control applicable)  
* **Optional:** Failover Test Reports

  
## A.8.15 Logging

**Description**  
Record events, exceptions, and other relevant security data to support monitoring and investigation.

**Technology**  
SIEM systems, centralized log management.

**Organization/processes**  
Define log retention, review procedures, and access restrictions.

**People**  
Train administrators on log analysis.

**Documentation**

- **Mandatory:** Logging Policy (if control applicable)
- **Optional:** Log Review Schedules


## A.8.16 Monitoring Activities

**Description**  
Monitor systems, networks, and applications for anomalies.

**Technology**  
IDS/IPS, SIEM, performance monitoring tools.

**Organization/processes**  
Establish thresholds for alerts, integrate monitoring with incident response.

**People**  
Train SOC teams on monitoring tools.

**Documentation**

- **Mandatory:** Monitoring Policy (if control applicable)
- **Optional:** Alert Handling Procedures


## A.8.17 Clock Synchronization

**Description**  
Synchronize system clocks to ensure accurate timestamps.

**Technology**  
NTP servers.

**Organization/processes**  
Enforce synchronization policy.

**People**  
Train IT staff on configuring NTP.

**Documentation**

- **Mandatory:** Time Synchronization Procedure (if control applicable)
- **Optional:** NTP Configuration Records


## A.8.18 Use of Privileged Utility Programs

**Description**  
Control and monitor the use of system utilities that can override security controls.

**Technology**  
Access control tools, PAM.

**Organization/processes**  
Limit access to authorized personnel, log usage.

**People**  
Train admins on secure use of utilities.

**Documentation**

- **Mandatory:** Privileged Utility Program Policy (if control applicable)
- **Optional:** Usage Logs


## A.8.19 Installation of Software on Operational Systems

**Description**  
Restrict software installation on production systems.

**Technology**  
Application whitelisting, endpoint security.

**Organization/processes**  
Approval process for software installation.

**People**  
Train users on installation policy.

**Documentation**

- **Mandatory:** Software Installation Policy (if control applicable)
- **Optional:** Installation Request Logs


## A.8.20 Networks Security

**Description**  
Protect network infrastructure from threats.

**Technology**  
Firewalls, IDS/IPS, VPN.

**Organization/processes**  
Segment networks, control traffic flows.

**People**  
Train staff on network security best practices.

**Documentation**

- **Mandatory:** Network Security Policy (if control applicable)
- **Optional:** Firewall Rules Documentation


## A.8.21 Security of Network Services

**Description**  
Ensure network services meet security requirements.

**Technology**  
Secure protocols, encrypted communication.

**Organization/processes**  
Define service security requirements.

**People**  
Train staff on secure network configuration.

**Documentation**

- **Mandatory:** Network Services Security Policy (if control applicable)
- **Optional:** Service Configuration Records


## A.8.22 Segregation of Networks

**Description**  
Separate networks based on sensitivity and usage.

**Technology**  
VLANs, network segmentation tools.

**Organization/processes**  
Document segmentation rules.

**People**  
Train network admins on segmentation principles.

**Documentation**

- **Mandatory:** Network Segregation Policy (if control applicable)
- **Optional:** Segmentation Maps


## A.8.23 Web Filtering

**Description**  
Control access to web resources to reduce security risks.

**Technology**  
Web proxy, URL filtering.

**Organization/processes**  
Define filtering categories.

**People**  
Train staff on acceptable use.

**Documentation**

- **Mandatory:** Web Filtering Policy (if control applicable)
- **Optional:** Blocklist/Allowlist Logs


## A.8.24 Use of Cryptography

**Description**  
Protect information using encryption and cryptographic controls.

**Technology**  
Encryption software, PKI.

**Organization/processes**  
Manage keys securely.

**People**  
Train staff on cryptography use.

**Documentation**

- **Mandatory:** Cryptography Policy (if control applicable)
- **Optional:** Key Management Logs


## A.8.25 Secure Development Life Cycle

**Description**  
Integrate security into the software development process.

**Technology**  
Static code analysis tools, DevSecOps pipelines.

**Organization/processes**  
Define security checkpoints.

**People**  
Train developers on secure coding.

**Documentation**

- **Mandatory:** Secure Development Policy (if control applicable)
- **Optional:** Development Checklists


## A.8.26 Application Security Requirements

**Description**  
Specify security requirements for applications.

**Technology**  
Requirements management tools.

**Organization/processes**  
Include security requirements in project plans.

**People**  
Train business analysts and developers.

**Documentation**

- **Mandatory:** Application Security Requirements Document (if control applicable)
- **Optional:** Requirements Traceability Matrix


## A.8.27 Secure System Architecture and Engineering Principles

**Description**  
Design systems with security principles in mind.

**Technology**  
Architecture modeling tools.

**Organization/processes**  
Document architecture decisions.

**People**  
Train architects on secure design.

**Documentation**

- **Mandatory:** Secure Architecture Document (if control applicable)
- **Optional:** Architecture Review Reports


## A.8.28 Secure Coding

**Description**  
Follow secure coding standards.

**Technology**  
Static analysis tools.

**Organization/processes**  
Adopt coding guidelines.

**People**  
Train developers.

**Documentation**

- **Mandatory:** Secure Coding Standards (if control applicable)
- **Optional:** Code Review Logs


## A.8.29 Security Testing in Development and Acceptance

**Description**  
Test security during development and before acceptance.

**Technology**  
Penetration testing tools.

**Organization/processes**  
Schedule security testing phases.

**People**  
Train testers on security testing.

**Documentation**

- **Mandatory:** Security Testing Plan (if control applicable)
- **Optional:** Test Reports


## A.8.30 Outsourced Development

**Description**  
Ensure outsourced development meets security requirements.

**Technology**  
Secure file sharing, encrypted communication.

**Organization/processes**  
Include security in contracts.

**People**  
Train procurement teams.

**Documentation**

- **Mandatory:** Outsourced Development Security Requirements (if control applicable)
- **Optional:** Supplier Security Assessments


## A.8.31 Separation of Development, Test and Production Environments

**Description**  
Separate environments to reduce risk.

**Technology**  
Virtualization, separate networks.

**Organization/processes**  
Control access between environments.

**People**  
Train admins.

**Documentation**

- **Mandatory:** Environment Separation Policy (if control applicable)
- **Optional:** Environment Access Logs


## A.8.32 Change Management

**Description**  
Control changes to systems.

**Technology**  
Change tracking software.

**Organization/processes**  
Approval workflows for changes.

**People**  
Train staff on change procedures.

**Documentation**

- **Mandatory:** Change Management Policy (if control applicable)
- **Optional:** Change Logs


## A.8.33 Test Information

**Description**  
Protect test data.

**Technology**  
Data anonymization tools.

**Organization/processes**  
Classify and handle test data securely.

**People**  
Train testers.

**Documentation**

- **Mandatory:** Test Data Protection Policy (if control applicable)
- **Optional:** Anonymization Logs


## A.8.34 Protection of Information Systems during Audit Testing

**Description**  
Ensure audits do not compromise system security.

**Technology**  
Audit-specific accounts, sandbox testing.

**Organization/processes**  
Review audit scope and methods.

**People**  
Train auditors on safe testing.

**Documentation**

- **Mandatory:** Audit Testing Security Procedure (if control applicable)
- **Optional:** Audit Test Logs

