# azure-identity-access-management
A Microsoft Entra ID and Azure RBAC portfolio project demonstrating identity management, least privilege, and access security

# Azure Identity and Access Management (IAM)

## Project Overview

This project demonstrates how to design a secure identity and access management environment using Microsoft Entra ID and Azure Role-Based Access Control (RBAC).

The scenario is based on a fictional company, Contoso Technologies, with employees across IT, Finance, and Human Resources.

The objective is to ensure that employees receive only the permissions required to perform their jobs, while privileged accounts receive additional protection.

## Business Scenario

Contoso Technologies needs a centralised identity management solution to:

- Manage employee identities.
- Organise employees into department-based groups.
- Assign permissions according to job responsibilities.
- Protect accounts using multifactor authentication.
- Restrict privileged administrative access.
- Monitor identity and access-related activity.

## Project Objectives

1. Design a Microsoft Entra ID identity structure.
2. Create a logical user and group management plan.
3. Implement an Azure RBAC permissions model.
4. Apply the principle of least privilege.
5. Design MFA and Conditional Access policies.
6. Document privileged identity management.
7. Develop an identity auditing and monitoring approach.

## Architecture

The proposed architecture follows this access flow:

**Employee → Microsoft Entra ID → Security Group → RBAC Role → Azure Resource**

Department-based groups will help manage permissions consistently.

## Technologies

| Technology | Purpose |
|---|---|
| Microsoft Entra ID | Identity and user management |
| Azure RBAC | Resource permissions |
| Conditional Access | Sign-in security policies |
| MFA | Additional authentication protection |
| Privileged Identity Management | Controlled privileged access |
| GitHub | Project documentation and version control |

## Security Principles

- Least privilege: users receive only the access they need.
- Role separation: ordinary users and administrators have different permissions.
- MFA: additional authentication protection for accounts.
- Privileged access control: administrator permissions are restricted.
- Auditing: identity-related activity should be traceable.

## Project Structure

```text
azure-identity-access-management/
│
├── README.md
├── architecture/
│   └── identity-architecture.png
├── users-and-groups/
│   ├── users.md
│   └── groups.md
├── rbac/
│   ├── role-assignment.md
│   └── permissions-matrix.md
├── security/
│   ├── mfa.md
│   ├── conditional-access.md
│   └── privileged-access.md
├── auditing/
│   └── audit-logs.md
```

## Testing and Evidence

Testing evidence, configuration examples, screenshots, and validation results will be added as the project develops.

Features that require paid Microsoft Entra licences will be identified separately from features that have been implemented and tested.

## Cost Considerations

This portfolio project is designed to be developed using free resources wherever possible. No paid Azure resources are required for the documentation and local scripting stages.

## Project Status

**In Progress**

## Learning Outcomes

By completing this project, I aim to demonstrate practical knowledge of:

- Identity and access management.
- Microsoft Entra ID.
- Azure RBAC.
- User and group administration.
- Least-privilege security.
- Authentication security.
- Identity auditing and administration.
