# 03 - Group Management

## Introduction

Groups are a fundamental component of Microsoft Entra ID and are used to simplify administration, manage access, and support collaboration.

Rather than assigning permissions individually to users, administrators can assign permissions to groups and manage membership centrally. This approach reduces administrative overhead, improves consistency, and supports security best practices.

Microsoft Entra ID supports multiple group types, the most common being Security Groups and Microsoft 365 Groups.

This chapter demonstrates how to create, manage, and review both group types while documenting the membership management process using a practical lab environment.

---

## Objectives

After completing this chapter, you should be able to:

- View existing groups
- Understand common Microsoft Entra group types
- Create a Security Group
- Add users to a Security Group
- Create a Microsoft 365 Group
- Add users to a Microsoft 365 Group
- Review group membership information
- Understand basic group administration concepts

---

## Prerequisites

Before starting this chapter, ensure you have:

- Access to Microsoft Entra Admin Center
- Administrative permissions
- Existing user accounts within the tenant
- Completed Chapter 02 – User Management

---

# Understanding Groups

Groups allow administrators to organise users and manage access efficiently.

Rather than assigning permissions directly to individual users, permissions can be assigned to groups. Users then inherit access through their group membership.

Common benefits include:

- Simplified administration
- Easier permission management
- Improved scalability
- Better security management

The two group types covered in this chapter are:

## Security Groups

Security Groups are primarily used for:

- Permission assignments
- Application access
- Resource access control
- Administrative delegation

## Microsoft 365 Groups

Microsoft 365 Groups are collaboration-focused groups that can provide:

- Shared mailbox functionality
- Shared calendar functionality
- Microsoft Teams integration
- SharePoint integration
- Collaboration features

---

# Viewing Existing Groups

## Navigation

Identity → Groups → All Groups

The All Groups page displays all groups available within the tenant.

Administrators can use this page to:

- Review existing groups
- Search for groups
- Create new groups
- Manage memberships

![Groups Overview](screenshots/groups-overview.png)

---

# Creating a Security Group

Security Groups are commonly used to manage access to applications, resources, and administrative functions.

## Navigation

Identity → Groups → New Group

Configure the following settings:

| Setting | Value |
|----------|----------|
| Group Type | Security |
| Group Name | IT Support Team |
| Description | IT Support Security Group |

Review the configuration before creating the group.

![Create Security Group](screenshots/create-security-group.png)

Select Create.

---

# Verifying Security Group Creation

After creation, return to the Groups list.

Verify that the new group appears successfully.

![Security Group Created](screenshots/security-group-created.png)

This confirms that the Security Group has been created successfully.

---

# Adding a Member to the Security Group

Open:

Groups → IT Support Team

Navigate to:

Members → Add Members

Select:

Helpdesk User

Review the selected user before adding them to the group.

![Add Member To Security Group](screenshots/add-member-to-security-group.png)

Complete the membership assignment.

---

# Verifying Security Group Membership

After adding the user, verify that Helpdesk User appears within the Members list.

![Security Group Membership Updated](screenshots/security-group-membership-updated.png)

This confirms that the membership assignment was successful.

---

# Creating a Microsoft 365 Group

Microsoft 365 Groups provide collaboration-focused functionality and are commonly used with Microsoft Teams, SharePoint, and Exchange Online.

## Navigation

Identity → Groups → New Group

Configure:

| Setting | Value |
|----------|----------|
| Group Type | Microsoft 365 |
| Group Name | IT Collaboration Team |
| Description | Microsoft 365 Collaboration Group |

Review the settings before creating the group.

![Create Microsoft 365 Group](screenshots/create-m365-group.png)

Select Create.

---

# Verifying Microsoft 365 Group Creation

Return to the Groups list and verify that the group appears successfully.

![Microsoft 365 Group Created](screenshots/m365-group-created.png)

This confirms that the Microsoft 365 Group was created successfully.

---

# Adding a Member to the Microsoft 365 Group

Open:

Groups → IT Collaboration Team

Navigate to:

Members → Add Members

Select:

Helpdesk User

Review the membership assignment before proceeding.

![Add Member To Microsoft 365 Group](screenshots/add-member-to-m365-group.png)

Complete the membership assignment.

---

# Verifying Microsoft 365 Group Membership

Verify that Helpdesk User appears within the Members list.

![Microsoft 365 Group Membership Updated](screenshots/m365-group-membership-updated.png)

This confirms that the user has been successfully added to the Microsoft 365 Group.

---

# Reviewing Group Properties

Group overview pages provide administrators with useful information including:

- Group type
- Membership information
- Owners
- Administrative settings
- Activity information

Open:

IT Support Team

Review the group overview page.

![Group Overview](screenshots/group-overview.png)

---

# Administrative Best Practices

When managing groups:

- Use groups instead of assigning permissions directly to users whenever possible
- Follow least privilege principles
- Review memberships regularly
- Remove inactive members when appropriate
- Document the purpose of important groups
- Assign group owners where appropriate

These practices improve security and simplify long-term administration.

---

# Key Learnings

This chapter demonstrated:

- Security Group creation
- Microsoft 365 Group creation
- Membership management
- Group administration
- Access management concepts
- Microsoft Entra group management fundamentals

---

# Skills Developed

By completing this chapter, the following skills were developed:

- Group Administration
- Identity Management
- Access Management
- Membership Administration
- Microsoft Entra Administration
- Technical Documentation
- GitHub Documentation

---

# Chapter Summary

In this chapter, group administration was performed within Microsoft Entra ID.

The following tasks were completed:

- Viewed existing groups
- Created a Security Group
- Added a user to the Security Group
- Created a Microsoft 365 Group
- Added a user to the Microsoft 365 Group
- Reviewed group properties and membership information

These activities represent common administrative tasks performed by Service Desk Analysts, Microsoft 365 Administrators, and Identity Administrators.
