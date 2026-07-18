# Enterprise Identity and Access Management (IAM) Using Microsoft Active Directory

## Project Overview

This project demonstrates the design, deployment, and administration of a complete on-premises enterprise Identity and Access Management (IAM) environment using Windows Server 2022 and Windows 8 Enterprise.

The environment simulates a multinational organization, **SAMSECOPS.ORG**, where centralized identity management, authentication, authorization, certificate-based trust, and security policy enforcement are implemented using Microsoft Active Directory technologies.

The project includes the deployment and configuration of Active Directory Domain Services (AD DS), Active Directory Certificate Services (AD CS), Domain Name System (DNS), Dynamic Host Configuration Protocol (DHCP), Organizational Units (OUs), Security Groups, Group Policy Objects (GPOs), and Public Key Infrastructure (PKI) to provide centralized administration and secure enterprise resource management.

---

# Technologies Used

- Windows Server 2022
- Windows 8 Enterprise
- Active Directory Domain Services (AD DS)
- Active Directory Certificate Services (AD CS)
- Public Key Infrastructure (PKI)
- Domain Name System (DNS)
- Dynamic Host Configuration Protocol (DHCP)
- Group Policy Management
- Microsoft Management Console (MMC)
- Windows PowerShell
- Windows Command Prompt
- Oracle VirtualBox
- TCP/IP Networking

---

# Project Objectives

- Deploy a Windows Server 2022 Domain Controller
- Configure Active Directory Domain Services (AD DS)
- Deploy Domain Name System (DNS)
- Configure Dynamic Host Configuration Protocol (DHCP)
- Design an enterprise Organizational Unit (OU) structure
- Create and manage users, computers, and security groups
- Implement Role-Based Access Control (RBAC)
- Configure and enforce Group Policy Objects (GPOs)
- Deploy Active Directory Certificate Services (AD CS)
- Configure an Enterprise Certification Authority
- Implement Public Key Infrastructure (PKI)
- Issue and validate trusted digital certificates

---

# Enterprise Environment

The project simulates a multinational organization operating across multiple geographical regions.

```
SAMSECOPS.ORG

├── United States
│   ├── IT
│   ├── Digital Marketing
│   └── Sales
│
├── United Kingdom
│   ├── Marketing
│   └── Human Resources
│
├── United Arab Emirates
│   ├── Finance
│   └── Consulting
│
└── Nigeria
    └── Warehouse
```

Each department contains dedicated Organizational Units (OUs), users, and security groups to simulate centralized enterprise administration.

---

# Infrastructure Configuration

| Component | Configuration |
|-----------|---------------|
| Domain | SAMSECOPS.ORG |
| Domain Controller | SAMSECOPS |
| Operating System | Windows Server 2022 |
| Client Operating System | Windows 8 Enterprise |
| Domain Controller IP | 10.0.5.5 (Static) |
| DNS Server | 10.0.5.5 |
| DHCP | Installed |
| Virtualization Platform | Oracle VirtualBox |

---

# Active Directory Implementation

The environment demonstrates:

- Active Directory forest deployment
- Domain Controller promotion
- Organizational Unit (OU) design
- User account administration
- Computer account management
- Security Group administration
- Role-Based Access Control (RBAC)
- Centralized authentication and authorization
- Password and account management

---

# Group Policy Implementation

Enterprise Group Policy Objects (GPOs) were created and linked to Organizational Units to centrally enforce security policies.

Implemented policies include:

- Restricting access to removable storage devices
- Certificate Auto-Enrollment
- Enterprise Certificate Policy

Policy deployment was validated using:

```powershell
gpupdate /force
```

---

# Active Directory Certificate Services (AD CS)

To extend the enterprise Identity and Access Management environment, Active Directory Certificate Services (AD CS) was deployed to establish a Public Key Infrastructure (PKI) for centralized certificate issuance and management.

The implementation includes:

- Enterprise Certification Authority deployment
- Certificate template configuration
- Certificate Auto-Enrollment
- User certificate enrollment
- Trusted Root Certification Authority configuration
- Certificate trust chain validation

The completed implementation demonstrates secure certificate-based authentication and centralized certificate lifecycle management within the Active Directory environment.

---


## 📸 Project Screenshots

### Active Directory Deployment
![Active Directory Installation](https://github.com/SamSecOps/IAM-On-prem-Using-Active-Directory/blob/main/Screenshots/Screenshot%202026-07-09%20163152.png)

### Domain Controller Promotion
![Domain Controller Promotion](https://github.com/SamSecOps/IAM-On-prem-Using-Active-Directory/blob/main/Screenshots/Screenshot%202026-07-09%20164054.png)

### Organizational Unit (OU) Structure
![Organizational Units](https://github.com/SamSecOps/IAM-On-prem-Using-Active-Directory/blob/main/Screenshots/Screenshot%202026-07-09%20192458.png)

### User and Security Group Management
![Active Directory Users and Computers](screenshots/ad-users-groups.png)

### Group Policy Management
![Group Policy](screenshots/group-policy.png)

### Windows 8 Client Joined to the Domain
![Domain Join](screenshots/domain-join.png)

### Active Directory Certificate Services (AD CS)
![AD CS Installation](screenshots/adcs-installation.png)

### Enterprise Certification Authority
![Certification Authority](screenshots/certification-authority.png)

### Certificate Templates
![Certificate Templates](screenshots/certificate-templates.png)

### Certificate Auto-Enrollment Policy
![Certificate Auto-Enrollment](screenshots/certificate-auto-enrollment.png)

### Issued User Certificate
![Issued Certificate](screenshots/issued-certificate.png)

### Certificate Trust Validation
![Certificate Trust Chain](screenshots/certificate-trust-chain.png)

---

# Key Skills Demonstrated

- Identity and Access Management (IAM)
- Active Directory Administration
- Windows Server Administration
- Active Directory Certificate Services (AD CS)
- Public Key Infrastructure (PKI)
- Role-Based Access Control (RBAC)
- Group Policy Management
- Windows Networking
- DNS Administration
- DHCP Administration
- Enterprise Authentication
- Certificate-Based Authentication
- Security Policy Enforcement

---

# Author

**Samuel O. Agboola**

Cybersecurity Analyst | Identity and Access Management | Active Directory | Windows Server | Public Key Infrastructure | Security Operations
