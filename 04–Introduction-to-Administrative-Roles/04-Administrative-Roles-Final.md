# 04 - Introduction to Administrative Roles

## Introduction

Microsoft Entra ID uses administrative roles to control access to management functions and administrative tasks across a tenant.

Rather than granting every administrator full control of the environment, Microsoft Entra ID implements Role-Based Access Control (RBAC), allowing permissions to be delegated according to job responsibilities. This approach improves security, reduces risk, and supports the Principle of Least Privilege.

In this chapter, administrative roles were reviewed, delegated administration was explored, and a complete role assignment lifecycle was performed, including assigning a role, verifying the assignment, removing the role, and validating the removal.

This chapter builds upon the user and group management concepts covered in previous chapters and introduces one of the most important security concepts in identity administration.

---

## Objectives

After completing this chapter, you should be able to:

- Understand Microsoft Entra administrative roles
- Understand Role-Based Access Control (RBAC)
- Review built-in administrative roles
- Understand the Global Administrator role
- Understand delegated administration concepts
- Assign administrative roles to users
- Remove administrative role assignments
- Apply the Principle of Least Privilege
- Review role permissions and responsibilities

---

## Prerequisites

Before starting this chapter, ensure you have:

- Access to Microsoft Entra Admin Center
- Administrative permissions
- Existing test users within the tenant
- Completed Chapters 01–03

---

# Understanding Administrative Roles

Administrative roles determine what actions a user can perform within Microsoft Entra ID.

Without roles, every administrator would require full access to the tenant, creating unnecessary security risks. Administrative roles allow organisations to delegate responsibilities while restricting access to only the permissions required for a specific job function.

Examples include:

- Global Administrator
- User Administrator
- Helpdesk Administrator
- Password Administrator
- Groups Administrator
- Authentication Administrator

Each role is designed to provide a specific set of permissions.

---

# Role-Based Access Control (RBAC)

Microsoft Entra ID uses Role-Based Access Control (RBAC) to manage administrative permissions.

RBAC works by assigning permissions to roles rather than directly to users. Users are then assigned the appropriate role based on their responsibilities.

Benefits of RBAC include:

- Improved security
- Reduced administrative complexity
- Easier auditing
- Better compliance
- Reduced risk of accidental changes

RBAC is a fundamental concept in modern identity and access management.

---

# Reviewing Available Administrative Roles

## Navigation

Identity → Roles & administrators

The Roles and Administrators page provides access to all built-in administrative roles available within Microsoft Entra ID.

Administrators can:

- Review available roles
- Search for specific roles
- Review assignments
- Assign permissions
- Manage delegated administration

![Roles and Administrators Overview](screenshots/roles-and-administrators-overview.png)

---

# Reviewing the Global Administrator Role

The Global Administrator role is the highest privileged built-in role within Microsoft Entra ID.

Users assigned this role have broad administrative control over the tenant and can manage most Microsoft cloud services.

Typical responsibilities include:

- User administration
- Group administration
- Security configuration
- Authentication settings
- Application management
- Tenant-wide administration

## Navigation

Identity → Roles & administrators

Search for:

Global Administrator

Open the role.

![Global Administrator Role](screenshots/global-administrator-role.png)

This screenshot also demonstrates how role assignments can be reviewed to identify which users currently hold privileged administrative access.

---

# Delegated Administration

Although Global Administrator provides extensive permissions, organisations should avoid assigning this role unnecessarily.

Instead, Microsoft Entra ID provides delegated roles that allow administrators to perform specific tasks without receiving full tenant-wide access.

Delegated administration helps organisations:

- Reduce security risks
- Limit exposure to privileged accounts
- Improve governance
- Follow security best practices

This concept forms the basis of the Principle of Least Privilege.

---

# Reviewing the Helpdesk Administrator Role

The Helpdesk Administrator role is an example of delegated administration.

This role is intended for Service Desk and IT Support personnel who require limited administrative capabilities.

Common responsibilities include:

- Supporting end users
- Performing password resets
- Managing basic identity-related requests
- Assisting with account access issues

## Navigation

Identity → Roles & administrators

Search for:

Helpdesk Administrator

Open the role.

![Helpdesk Administrator Overview](screenshots/helpdesk-role-overview.png)

Reviewing role descriptions helps administrators understand what permissions are available and whether a role is appropriate for a particular user.

---

# Assigning an Administrative Role

To demonstrate delegated administration, the Helpdesk Administrator role was temporarily assigned to the Helpdesk User account.

## Navigation

Helpdesk Administrator → Assignments → Add assignments

Search for:

Helpdesk User

Select the user and review the assignment before proceeding.

![Assign Role to User](screenshots/assign-role-to-user.png)

Once verified, complete the assignment.

---

# Verifying the Role Assignment

After the assignment is completed, review the Assignments page to verify that the user has been added successfully.

![Role Assignment Complete](screenshots/role-assignment-complete.png)

This confirms that the Helpdesk User account has received the Helpdesk Administrator role.

Verifying administrative changes is an important best practice and helps ensure that assignments are completed successfully.

---

# Removing an Administrative Role

Administrative permissions should only be assigned when required.

To demonstrate proper administrative governance, the role assignment was removed after testing.

## Navigation

Helpdesk Administrator → Assignments

Select:

Helpdesk User

Choose:

Remove assignments

The following confirmation window is displayed.

![Remove Role Assignment](screenshots/remove-role-assignment.png)

Review the action before confirming the removal.

---

# Verifying Role Removal

After confirming the removal, return to the Assignments page and verify that the user no longer appears within the role assignments list.

![Role Assignment Removed](screenshots/role-assignment-removed.png)

This confirms that the role has been removed successfully and that the user no longer possesses the delegated administrative permissions.

---

# Reviewing Role Permissions

Role descriptions provide valuable information regarding responsibilities, permissions, and intended use cases.

Open:

Helpdesk Administrator → Description

Review the information provided.

![Role Overview Summary](screenshots/role-overview-summary.png)

Understanding role capabilities is essential when determining the most appropriate level of access for administrators.

---

# Principle of Least Privilege

The Principle of Least Privilege is one of the most important concepts in identity and access management.

The principle states that users and administrators should receive only the permissions necessary to perform their duties.

Benefits include:

- Reduced attack surface
- Reduced risk of misuse
- Improved security posture
- Better compliance
- Improved accountability

This chapter demonstrated the principle by:

- Assigning a role only when required
- Verifying the assignment
- Removing the role when no longer needed
- Verifying the removal

These actions reflect real-world administrative and security practices.

---

# Administrative Best Practices

When managing administrative roles:

- Limit Global Administrator assignments
- Use delegated roles whenever possible
- Follow least privilege principles
- Review assignments regularly
- Remove unnecessary permissions promptly
- Document administrative changes
- Periodically audit privileged accounts

These practices help maintain a secure and well-governed Microsoft Entra environment.

---

# Key Learnings

This chapter demonstrated:

- Administrative role management
- Role-Based Access Control (RBAC)
- Global Administrator review
- Delegated administration concepts
- Administrative role assignment
- Administrative role removal
- Least privilege implementation
- Security-focused administration

---

# Skills Developed

By completing this chapter, the following skills were developed:

- Microsoft Entra Administration
- Administrative Role Management
- Role-Based Access Control (RBAC)
- Identity Governance Awareness
- Security Administration
- Access Management
- Technical Documentation
- GitHub Documentation

---

# Chapter Summary

In this chapter, Microsoft Entra administrative roles were reviewed and managed.

The following tasks were completed:

- Reviewed available administrative roles
- Examined the Global Administrator role
- Reviewed delegated administration concepts
- Examined the Helpdesk Administrator role
- Assigned an administrative role to a user
- Verified the assignment
- Removed the assignment
- Verified role removal
- Applied the Principle of Least Privilege

These activities represent common administrative tasks performed by Microsoft 365 Administrators, Identity Administrators, Security Administrators, and Service Desk professionals.

Understanding administrative roles and delegated permissions is essential for maintaining a secure Microsoft Entra environment and forms a foundation for more advanced identity governance topics.
