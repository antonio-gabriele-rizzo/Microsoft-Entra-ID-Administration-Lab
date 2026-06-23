# 07 - Monitoring and Audit Logs

## Introduction

Monitoring and auditing are essential components of identity administration. Microsoft Entra ID provides administrators with visibility into authentication activity, user access patterns, and administrative actions performed within the tenant.

Sign-in Logs help administrators investigate authentication events and troubleshoot access issues, while Audit Logs provide a record of configuration changes and administrative operations such as password resets, user modifications, role assignments, and group management.

In this chapter, monitoring capabilities within Microsoft Entra ID were explored through Sign-in Logs and Audit Logs, including filtering and investigating password reset events.

---

## Objectives

After completing this chapter, you should be able to:

- Access Sign-in Logs
- Review authentication activity
- Filter sign-in events
- Access Audit Logs
- Review administrative actions
- Filter audit records
- Investigate password reset events
- Apply monitoring and troubleshooting workflows

---

## Prerequisites

- Access to Microsoft Entra Admin Center
- Administrative permissions
- Existing test users
- Microsoft Entra ID tenant
- Completed Chapters 01–06

---

# Understanding Monitoring in Microsoft Entra ID

Monitoring allows administrators to review user activity, authentication events, and administrative operations.

Microsoft Entra ID provides several monitoring tools, including:

- Sign-in Logs
- Audit Logs
- Provisioning Logs
- Service Health (licensing dependent)
- Log Analytics integration (licensing dependent)

These tools assist with troubleshooting, compliance, and security investigations.

---

# Reviewing Sign-in Logs

## Navigation

Monitoring & Health → Sign-in logs

![Sign-in Logs Overview](screenshots/signin-logs-overview.png)

The Sign-in Logs page provides visibility into authentication activity across the tenant.

Administrators can review:

- User sign-ins
- Application access
- Authentication status
- Source IP addresses
- Timestamps
- Conditional Access outcomes

This information is useful when troubleshooting authentication issues and investigating user activity.

---

# Filtering Sign-in Logs

## Navigation

Sign-in logs → Add filters

![Sign-in Log Filters](screenshots/signin-log-filters.png)

Filtering allows administrators to narrow results based on:

- User
- Application
- Date range
- Status
- Location

Filtering improves investigation efficiency when reviewing large volumes of authentication data.

---

# Reviewing Tenant Sign-in Activity

## Navigation

Monitoring & Health → Sign-in logs

![Tenant Sign-in Logs](screenshots/tenant-signin-logs.png)

Tenant-wide Sign-in Logs provide a broader view of authentication activity across the organisation.

Information available includes:

- User accounts
- Applications accessed
- Sign-in status
- Source IP addresses
- Event timestamps

These logs are commonly used by Service Desk staff, Identity Administrators, and Security Administrators.

---

# Reviewing Audit Logs

## Navigation

Monitoring & Health → Audit logs

![Audit Logs Overview](screenshots/audit-logs-overview.png)

Audit Logs track administrative actions performed within Microsoft Entra ID.

Examples include:

- User creation
- User deletion
- Password resets
- Group modifications
- Role assignments
- Policy changes

Audit Logs provide accountability and support compliance requirements.

---

# Filtering Audit Logs

## Navigation

Audit logs → Activity filter

![Audit Logs Filter Password Reset](screenshots/audit-logs-filter-password-reset.png)

To investigate password reset activity, the Activity filter was used to search for:

- Reset user password

Filtering allows administrators to quickly locate specific administrative actions.

---

# Investigating Password Reset Events

## Navigation

Audit logs → Activity: Reset user password

![Audit Logs Password Reset Events](screenshots/audit-logs-password-reset-events.png)

The filtered results display password reset operations performed within the tenant.

Available information includes:

- Date and time
- Service
- Category
- Activity performed
- Status
- Initiating administrator

This information provides traceability and administrative accountability.

---

# Monitoring and Troubleshooting Use Cases

Sign-in Logs and Audit Logs support several common administrative tasks.

### Authentication Troubleshooting

Administrators can investigate:

- Failed sign-ins
- Successful authentications
- MFA issues
- User access problems

### Security Investigations

Logs can be reviewed to:

- Identify unusual activity
- Investigate suspicious sign-ins
- Track administrative actions
- Support incident response

### Compliance and Auditing

Audit records help organisations:

- Demonstrate accountability
- Track configuration changes
- Review administrative activity
- Support compliance reporting

---

# Lab Limitations

This lab environment used Microsoft Entra ID Free.

Some monitoring features were unavailable due to licensing restrictions, including:

- Service Health dashboards
- Log Analytics integration

Despite these limitations, Sign-in Logs and Audit Logs provided sufficient functionality to demonstrate core monitoring and auditing workflows.

---

# Key Learnings

This chapter demonstrated:

- Sign-in Log review
- Authentication monitoring
- Sign-in Log filtering
- Audit Log review
- Audit Log filtering
- Password reset investigations
- Administrative accountability
- Monitoring workflows

---

# Skills Developed

By completing this chapter, the following skills were developed:

- Identity Monitoring
- Authentication Analysis
- Audit Log Investigation
- Troubleshooting Workflows
- Security Monitoring
- Microsoft Entra Administration
- Service Desk Investigation Techniques
- Technical Documentation

---

# Chapter Summary

In this chapter, Microsoft Entra ID monitoring capabilities were explored through Sign-in Logs and Audit Logs.

The following activities were completed:

- Reviewed Sign-in Logs
- Filtered authentication events
- Examined tenant-wide sign-in activity
- Reviewed Audit Logs
- Filtered audit records
- Investigated password reset events
- Applied monitoring and troubleshooting workflows

Monitoring and auditing are critical administrative functions that provide visibility into authentication activity and administrative operations. Understanding how to analyse Sign-in Logs and Audit Logs is an essential skill for Identity Administrators, Security Administrators, and Service Desk professionals.
