# TechLab Microsoft Entra ID Administration Portfolio

![Status](https://img.shields.io/badge/Status-In%20Progress-blue)
![Platform](https://img.shields.io/badge/Platform-Microsoft%20Entra%20ID-0078D4)
![PowerShell](https://img.shields.io/badge/PowerShell-Automation-5391FE)
![Portfolio](https://img.shields.io/badge/Portfolio-Project-success)

## About This Project

Welcome to my TechLab Microsoft Entra ID Administration Portfolio.

This repository documents my hands-on learning journey in Microsoft Entra ID administration using the same Microsoft 365 tenant developed throughout the TechLab Microsoft 365 Portfolio.

The purpose of this project is threefold:

1. Develop practical Microsoft Entra ID administration skills.
2. Build a professional portfolio demonstrating real-world identity management tasks.
3. Create a personal technical reference and learning resource that can be revisited in the future.

Every section is documented using step-by-step procedures, screenshots, explanations, and practical examples to support both learning and future reference.

---

## TechLab Portfolio Series

This repository is part of the TechLab portfolio series, a collection of hands-on IT administration projects focused on Microsoft cloud technologies, identity management, endpoint administration, automation, networking, and IT support.

### Current Projects

- TechLab Microsoft 365 Portfolio
- TechLab Microsoft Entra ID Administration Portfolio

### Planned Projects

- TechLab Microsoft Intune Administration Portfolio
- TechLab Active Directory Administration Portfolio
- TechLab Service Desk Troubleshooting Portfolio

---

## Project Objectives

- Understand Microsoft Entra ID fundamentals
- Learn cloud identity management concepts
- Manage users and groups
- Explore administrative roles and delegated permissions
- Configure and understand Multi-Factor Authentication (MFA)
- Manage passwords and account recovery
- Review sign-in and audit logs
- Learn basic Microsoft Graph PowerShell administration
- Build professional technical documentation using GitHub and Markdown
- Create a reusable Microsoft Entra ID administration reference guide

---

## Environment

| Setting | Value |
|----------|----------|
| Tenant Name | TechLab |
| Platform | Microsoft Entra Admin Center |
| Licence | Microsoft Entra ID Free |
| Purpose | Learning, Documentation and Portfolio Development |

---

## Project Structure

| Section | Status |
|----------|----------|
| [01 - Identity Overview](01-Identity-Overview/Identity-Overview.md) | ✅ Complete |
| [02 - User Management](02-User-Management/User-Management.md) | ✅ Complete |
| [03 - Group Management](03-Group-Management/Group-Management.md) | ✅ Complete |
| [04 - Introduction to Administrative Roles](04-Administrative-Roles/Administrative-Roles.md) | ✅ Complete |
| [05 - Multi-Factor Authentication (MFA)](05-Multi-Factor-Authentication/Multi-Factor-Authentication.md) | ✅ Complete |
| [06 - Password Management](06–Password-Management/Password-Management.md) | ✅ Complete |
| [07 - Monitoring and Audit Logs](07-Monitoring-and-Audit-Logs/Monitoring-and-Audit-Logs.md) | ✅ Complete |
| [08 - Basic Microsoft Graph PowerShell](08-Basic-Microsoft-Graph-PowerShell/Basic-Microsoft-Graph-PowerShell.md) | ✅ Complete |
| 09 - Troubleshooting Scenarios | ⏳ Planned |

---

## Section Overview

### 01 – Identity Overview

Introduction to Microsoft Entra ID and cloud identity management.

Topics covered:

- Microsoft Entra ID fundamentals
- Identity management concepts
- Authentication vs Authorisation
- Microsoft Entra Admin Center
- Accessing the Entra portal
- User management overview

Skills developed:

- Identity and Access Management (IAM) fundamentals
- Cloud identity concepts
- Microsoft Entra navigation

---

### 02 – User Management

User lifecycle administration within Microsoft Entra ID.

This chapter provides a practical step-by-step guide to creating, managing, disabling, deleting, and restoring user accounts within Microsoft Entra ID.

Topics covered:

- User overview and user account information
- User creation
- User properties and profile information
- Account enable and disable operations
- Password reset fundamentals
- User deletion
- Deleted users management
- User restoration
- Administrative best practices for user management

Skills developed:

- User administration
- Identity management
- Service Desk procedures
- User lifecycle management
- Microsoft Entra administration

---

### 03 – Group Management

Group administration and membership management.

This chapter provides a practical introduction to creating and managing groups within Microsoft Entra ID, including Security Groups and Microsoft 365 Groups.

Topics covered:

- Security Groups
- Microsoft 365 Groups
- Group creation
- Group ownership
- Membership management
- Adding and removing members
- Group administration
- Access management concepts

Skills developed:

- Group administration
- Membership management
- Access management
- Permission management
- Microsoft Entra administration

---

### 04 – Introduction to Administrative Roles

Introduction to delegated administration, Role-Based Access Control (RBAC), and administrative permissions within Microsoft Entra ID.

This chapter provides a practical introduction to Microsoft Entra administrative roles, delegated administration, and the Principle of Least Privilege.

Topics covered:

- Administrative roles overview
- Role-Based Access Control (RBAC)
- Global Administrator
- Helpdesk Administrator
- Delegated administration
- Administrative role assignments
- Administrative role removal
- Principle of Least Privilege
- Administrative security best practices

Skills developed:

- Administrative role management
- Role-Based Access Control (RBAC)
- Delegated administration
- Identity governance awareness
- Security administration
- Access management

---

### 05 – Multi-Factor Authentication (MFA)

Identity security, authentication methods, and Multi-Factor Authentication (MFA) administration within Microsoft Entra ID.

This chapter introduces Multi-Factor Authentication concepts, authentication method policies, Microsoft Authenticator configuration, user authentication methods, and MFA security best practices.

Topics covered:

- Multi-Factor Authentication (MFA) fundamentals
- Authentication factors
- Authentication method policies
- Microsoft Authenticator
- User authentication methods
- MFA re-registration
- Authentication method evaluation
- Passwordless authentication overview
- Security best practices

Skills developed:

- Identity security
- Multi-Factor Authentication administration
- Authentication method management
- Microsoft Entra administration
- Security administration
- Access management

---

### 06 – Password Management

Password administration, account recovery, and authentication troubleshooting within Microsoft Entra ID.

This chapter explores password reset procedures, temporary password generation, authentication method review, session revocation, account recovery processes, and sign-in log investigation.

Topics covered:

- Password reset procedures
- Temporary password generation
- Force password change at next sign-in
- Account recovery
- Authentication methods review
- Session revocation
- Sign-in log investigation
- Password security best practices

Skills developed:

- Password administration
- Identity management
- Account recovery
- Authentication troubleshooting
- Security administration
- User support
- Service Desk procedures
- Microsoft Entra administration

---

### 07 – Monitoring and Audit Logs

Monitoring, auditing, and troubleshooting identity activity within Microsoft Entra ID.

This chapter explores Sign-in Logs and Audit Logs, demonstrating how administrators investigate authentication activity, filter events, review administrative operations, and analyse password reset records.

Topics covered:

- Sign-in Logs
- Sign-in event filtering
- Tenant-wide authentication monitoring
- Audit Logs
- Audit Log filtering
- Password reset investigations
- Administrative accountability
- Monitoring and troubleshooting workflows

Skills developed:

- Identity monitoring
- Authentication analysis
- Audit Log investigation
- Security monitoring
- Troubleshooting workflows
- Administrative auditing
- Microsoft Entra administration

---

### 08 – Basic Microsoft Graph PowerShell

Introduction to Microsoft Graph PowerShell for modern Microsoft Entra ID administration.

This chapter demonstrates how to connect to Microsoft Graph, review connection context information, retrieve users and groups, and manage authenticated PowerShell sessions using the Microsoft Graph SDK.

Topics covered:

- Microsoft Graph PowerShell module
- Connect-MgGraph
- Get-MgContext
- Get-MgUser
- Get-MgGroup
- Disconnect-MgGraph
- Session management

Skills developed:

- Microsoft Graph administration
- PowerShell administration
- Identity management
- User management
- Group management
- Cloud administration
- Modern Microsoft administration

---

### 09 – Troubleshooting Scenarios

Common Microsoft Entra ID support scenarios.

Topics covered:

- User sign-in issues
- Password problems
- MFA issues
- Access problems
- Administrative troubleshooting

Skills developed:

- Troubleshooting methodology
- Incident investigation
- Service Desk skills

---

## Documentation Methodology

Each section follows a consistent documentation structure:

- Objectives
- Step-by-step procedures
- Screenshots and evidence
- Technical explanations
- Administrative tasks performed
- Key learnings
- Skills developed

The goal is to ensure that every documented task can be reproduced in the future and used as a practical reference guide.

---

## Skills Demonstrated

### Identity Administration

- User lifecycle management
- Group administration
- Password management
- Administrative role assignment

### Security Administration

- Multi-Factor Authentication (MFA)
- Authentication methods
- Sign-in monitoring
- Audit log analysis

### Automation

- Microsoft Graph PowerShell
- Administrative reporting
- CSV exports
- PowerShell automation

### Professional Skills

- Technical Documentation
- GitHub Version Control
- Markdown Documentation
- Troubleshooting Methodology

---

## Future Projects

The TechLab portfolio will continue to expand with additional projects including:

- Microsoft Intune Administration
- Active Directory Administration
- Service Desk Troubleshooting
- Endpoint Management
- Jamf Awareness
- Advanced Microsoft Graph Automation

---

## Career Relevance

This portfolio supports my professional development towards roles such as:

- IT Support Technician
- Service Desk Analyst
- Microsoft 365 Administrator
- Junior Systems Administrator
- Cloud Support Technician

---

## Notes

This repository is a personal learning environment created for educational and portfolio purposes.

All activities are performed within a dedicated Microsoft cloud test environment.

---

## Author

**Antonio Gabriele Rizzo**

- CompTIA Tech+
- CompTIA A+
- Junior Network Engineer
- Microsoft 365 Administration
- Microsoft Entra ID Administration
- Aspiring Cloud and Infrastructure Professional

---

## Connect

GitHub Portfolio:

https://github.com/antonio-gabriele-rizzo
