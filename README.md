# Project 9: Domain Controller Setup

## Project Objective
To understand and implement basic authentication and centralized user management using Active Directory Domain Services (AD DS) in a Windows Server environment, establishing a foundational domain controller for enterprise-level identity and access management.

---

## Overview
This project demonstrates the installation, configuration, and operational setup of Active Directory Domain Services on Windows Server, establishing a functional domain infrastructure with centralized user authentication and management capabilities.

---

## Key Activities

### 1. Active Directory Domain Services Installation
- Installed the AD DS role on Windows Server
- Configured required dependencies and prerequisites

### 2. Domain Controller Configuration
- Promoted Windows Server to a Domain Controller
- Established a new Active Directory forest: `lab.local`
- Configured DNS services for domain name resolution

### 3. User Account Creation
- Created two domain user accounts:
  - `rahul1`
  - `rahul2`
- Both accounts verified and functional within the domain

### 4. Credential Verification
- Validated user accounts through Active Directory Users and Computers console
- Tested and verified credentials using PowerShell authentication methods
- Confirmed successful domain integration for both user accounts

---

## Results Achieved

✅ **Successfully deployed** a Windows Server Domain Controller with AD DS role installed  
✅ **Established** domain infrastructure with `lab.local` forest and DNS integration  
✅ **Created and verified** two operational domain user accounts with active directory credentials  
✅ **Demonstrated** centralized user management and authentication capabilities  
✅ **Validated** credential verification using both GUI and PowerShell tools  

---

## Technologies & Tools Used

| Component | Purpose |
|-----------|---------|
| **Windows Server** | Domain Controller platform |
| **Active Directory Domain Services (AD DS)** | Centralized identity and access management |
| **DNS** | Domain name resolution and AD integration |
| **PowerShell** | User verification and credential testing |
| **Active Directory Users and Computers** | User account management and administration |

---

## Deliverables

| # | Deliverable | Status |
|---|-------------|--------|
| 01 | AD DS Installation Screenshot | ✓ |
| 02 | Domain Controller Configuration | ✓ |
| 03 | Active Directory Users Display | ✓ |
| 04 | PowerShell User Verification | ✓ |
| 05 | Rahul1 Credential Verification | ✓ |
| 06 | Rahul2 Credential Verification | ✓ |

*All screenshots are located in the `/screenshots` folder*

---

## Outcomes & Impact

This project successfully demonstrates:

- **Centralized Authentication**: Implemented domain-based authentication replacing local machine authentication
- **User Management**: Established centralized identity management for multiple users
- **Enterprise Readiness**: Created foundational infrastructure for multi-user enterprise environments
- **AD Infrastructure**: Built operational Active Directory forest with functional domain controller
- **Scalability**: Demonstrated framework ready for adding additional users and resources

---

## Notes

- Interactive login testing using `runas` was restricted due to organization's training environment security policies
- All user credential verification was performed programmatically using PowerShell authentication methods
- Domain controller is fully operational and ready for additional user and computer deployments

---

## Project Status

**Status**: ✅ **COMPLETED**

All objectives achieved. Domain controller fully operational with verified user accounts and centralized authentication infrastructure in place.
