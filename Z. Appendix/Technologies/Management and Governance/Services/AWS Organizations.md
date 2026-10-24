---
group:
  - technology
---
AWS Organizations is a service that helps you centrally manage and govern your environment as you grow and scale your AWS resources. It allows you to centrally manage multiple AWS accounts, apply governance policies across accounts, and simplify billing.

## Key Features

- **Centralized account management**: Manage multiple AWS accounts from a single place.
- **Hierarchical organization**: Group accounts into organizational units (OUs).
- **Policy-based management**: Apply policies to groups of accounts.
- **Service control policies (SCPs)**: Centrally control AWS service use across accounts.
- **Tag policies**: Standardize tags across resources in your organization.
- **Backup policies**: Centrally manage AWS Backup plans across accounts.
- **AI services opt-out policies**: Control AI service data usage across accounts.
- **Consolidated billing**: Single payment method for all accounts.
- **Volume discounts**: Pricing benefits from combined usage across accounts.
- **Reserved instance sharing**: Share reserved instances across accounts.
- **Savings Plans sharing**: Share Savings Plans across accounts.
- **Account creation API**: Programmatically create new AWS accounts.
- **Integration with AWS services**: Work with other AWS services like Control Tower, IAM, and Config.
- **Resource sharing**: Share resources across accounts using AWS RAM.
- **Cross-account role access**: Easily switch between accounts using IAM roles.

## Organization Structure

- **Management account**: The central account that creates and manages the organization.
- **Member accounts**: Individual AWS accounts that are part of the organization.
- **Root**: The top-level container for all accounts and organizational units.
- **Organizational units (OUs)**: Containers for accounts that allow hierarchical structuring.
- **Policies**: Rules that apply to accounts and OUs.
- **Invitations**: Method to add existing accounts to an organization.
- **Handshakes**: Approval process for account management actions.
- **Delegation**: Assign administrative responsibilities to member accounts.
- **Service principals**: Allow AWS services to perform tasks in your organization.

## Policy Types

- **Service control policies (SCPs)**: Control which AWS service actions are allowed.
- **Tag policies**: Define how resources should be tagged.
- **Backup policies**: Define backup plans for resources.
- **AI services opt-out policies**: Control AI service data usage.
- **Permissions boundaries**: Define maximum permissions for IAM entities.
- **Inheritance rules**: Determine how policies apply to child OUs and accounts.
- **Policy evaluation logic**: Rules for how different policies interact.
- **Effective policies**: The combination of all applicable policies.

## Common Use Cases

- **Multi-account strategies**: Implement security and compliance through account separation.
- **Environment segregation**: Separate development, testing, and production environments.
- **Business unit alignment**: Align accounts with organizational structure.
- **Centralized governance**: Apply consistent policies across accounts.
- **Cost management**: Centralize and optimize AWS spending.
- **Security controls**: Implement organization-wide security policies.
- **Compliance frameworks**: Enforce compliance requirements across accounts.
- **Resource sharing**: Share resources across accounts efficiently.
- **Identity federation**: Integrate with corporate identity providers.
- **Service enablement control**: Control which services can be used in accounts.

## AWS Organizations and Other AWS Services

Organizations integrates with many AWS services, including:
- **AWS Control Tower**: Set up and govern a multi-account environment.
- **AWS IAM Identity Center**: Single sign-on for all accounts.
- **AWS Config**: Assess, audit, and evaluate configurations across accounts.
- **AWS CloudTrail**: Track user activity and API usage across accounts.
- **AWS Backup**: Centrally manage backups across accounts.
- **AWS Security Hub**: Centralize security findings across accounts.
- **AWS License Manager**: Manage licenses across accounts.
- **AWS Firewall Manager**: Centrally configure AWS WAF rules.
- **AWS Resource Access Manager**: Share resources across accounts.
- **AWS Service Catalog**: Control available services across accounts.

## Benefits

- **Simplified account management**: Manage multiple accounts from a single console.
- **Enhanced security**: Apply security policies consistently across accounts.
- **Cost savings**: Consolidated billing and volume discounts.
- **Operational efficiency**: Standardize configurations and processes.
- **Improved governance**: Enforce policies at scale.
- **Flexible structure**: Adapt organizational structure to your needs.
- **Automated account provisioning**: Create and configure accounts programmatically.
- **Centralized auditing**: Track activities across all accounts.
- **Streamlined compliance**: Implement compliance requirements consistently.
- **Resource optimization**: Share resources and reservations efficiently.

## Pricing

AWS Organizations is available at no additional charge. You only pay for the AWS resources you create and use in your accounts, based on the standard pricing for those services.