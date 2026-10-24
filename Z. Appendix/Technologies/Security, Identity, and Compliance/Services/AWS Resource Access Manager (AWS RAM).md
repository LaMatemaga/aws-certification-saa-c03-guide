---
group:
  - technology
---
AWS Resource Access Manager (RAM) enables you to securely share your resources across AWS accounts, within your organization, or with specific AWS principals. It provides a simple, consistent way to share resources including transit gateways, subnets, license configurations, and more.

## Key Features

- **Resource sharing**: Share AWS resources across accounts or within your organization.
- **Fine-grained access control**: Define specific permissions for shared resources.
- **Centralized management**: Manage all resource sharing from a single place.
- **AWS Organizations integration**: Share resources with all accounts in your organization.
- **Resource sharing invitations**: Send and manage invitations for resource sharing.
- **Sharing monitoring**: View and track resource sharing details.
- **Controlled access**: Resource owners maintain full control of shared resources.
- **API access**: Programmatically manage resource sharing.

## Shareable Resource Types

AWS RAM supports sharing many resource types, including:

- **Networking**:
    - VPC subnets
    - Transit gateways
    - Traffic Mirror targets
    - Prefix Lists
    - Route 53 Resolver rules
    - Network Firewall policies
- **Compute and containers**:
    - EC2 Capacity Reservations
    - EC2 Dedicated Hosts
    - ECS task definitions
    - Systems Manager parameters
- **Storage and databases**:
    - Aurora DB clusters
    - FSx for Lustre file systems
    - FSx for Windows File Server file systems
    - License Manager configurations
- **Security and identity**:
    - AWS Certificate Manager Private CA
    - ACM certificates
- **Others**:
    - CodeBuild projects
    - License Manager configurations
    - Resource Groups
    - CloudFormation StackSets
    - Outposts resources

## Sharing Options

- **Share with specific AWS accounts**: Share resources with specific accounts by account ID.
- **Share with your organization**: Share with all accounts in your AWS Organizations.
- **Share with organizational units**: Share with specific OUs in your AWS Organizations.
- **Share with IAM roles or users**: Share with specific IAM principals.

## Common Use Cases

- **Multi-account architectures**: Share resources across accounts in a multi-account strategy.
- **Shared services model**: Create a central account for shared resources.
- **Centralized networking**: Manage networking components from a central account.
- **Development and testing**: Share resources between development and testing environments.
- **Cost optimization**: Share expensive resources to reduce costs.
- **License management**: Centralize license management across accounts.
- **Partner access**: Provide partners with access to specific resources.
- **Team collaboration**: Share resources between teams in different accounts.

## Benefits

- **Simplified sharing**: Share resources with a few clicks or API calls.
- **Reduced costs**: Avoid duplicating resources across accounts.
- **Centralized management**: Manage shared resources from a single place.
- **Improved security**: Maintain control over shared resources.
- **Operational efficiency**: Reduce management overhead of cross-account sharing.
- **Consistent access control**: Apply consistent access control to shared resources.

## Best Practices

- **Organize by function**: Group resources by their function when sharing.
- **Least privilege**: Share resources with minimum necessary permissions.
- **Monitor sharing**: Regularly review shared resources and permissions.
- **Use AWS Organizations**: Leverage AWS Organizations for simplified sharing.
- **Document sharing**: Document resource sharing policies and procedures.
- **Regular audits**: Regularly audit resource sharing to ensure compliance.

## Pricing

AWS Resource Access Manager is provided at no additional charge. You only pay for the resources you create and share through the service.