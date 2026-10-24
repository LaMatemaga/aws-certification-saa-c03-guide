---
group:
  - technology
---
AWS Identity and Access Management (IAM) enables you to securely control access to AWS services and resources. Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources.

## Key Components

### Principal Entities

- **Users**: Individual people or applications that need AWS access.
- **Groups**: Collections of IAM users for easier permission management.
- **Roles**: Set of permissions that can be assumed by trusted entities (users, applications, or AWS services).

### Access Management Tools

- **Policies**: JSON documents defining permissions.
- **Permission boundaries**: Set maximum permissions an IAM entity can have.
- **Service control policies (SCPs)**: Organization-level permission boundaries.
- **Session policies**: Limit permissions for temporary sessions.
- **Resource-based policies**: Attached directly to resources (e.g., S3 bucket policies).

### Security Features

- **Multi-factor authentication (MFA)**: Additional security for user sign-in.
- **Credential rotation**: Manage and rotate access keys.
- **Password policies**: Enforce password complexity requirements.
- **Access Analyzer**: Identify resources shared with external entities.
- **Last accessed information**: View when services were last accessed.

## Policy Types

- **Identity-based policies**: Attached to IAM identities (users, groups, roles).
- **Resource-based policies**: Attached directly to resources.
- **Permissions boundaries**: Set maximum permissions for an entity.
- **Organizations SCPs**: Control permissions across AWS accounts.
- **Access control lists (ACLs)**: Control which principals can access resources.
- **Session policies**: Limit permissions for temporary sessions.

## Access Control Methods

- **Attribute-based access control (ABAC)**: Define permissions based on tags.
- **Role-based access control (RBAC)**: Define permissions based on job functions.
- **Least privilege principle**: Grant only permissions required for tasks.
- **Temporary credentials**: Use short-lived credentials for enhanced security.

## Common Use Cases

- **User access management**: Manage access for IAM users and groups.
- **Application access**: Provide AWS access to applications with IAM roles.
- **Cross-account access**: Enable secure access between AWS accounts.
- **AWS service access**: Allow AWS services to access other services.
- **Federated access**: Enable access for users authenticated by external identity providers.
- **Mobile app access**: Secure AWS resource access from mobile applications.
- **Workload identity**: Assign identities to applications and services.

## Best Practices

- **Root user protection**: Secure and minimize use of the root user account.
- **Individual user accounts**: Create individual users for each person.
- **Least privilege**: Grant minimum permissions needed.
- **Use groups**: Assign policies to groups rather than individual users.
- **Enforce MFA**: Require MFA for all users, especially privileged users.
- **Rotate credentials**: Regularly rotate passwords and access keys.
- **Remove unnecessary credentials**: Remove unused users and credentials.
- **Use conditions in policies**: Restrict access based on IP address, time, and MFA.
- **Monitor activity**: Review AWS CloudTrail logs and IAM reports.

## AWS Service Integrations

IAM integrates with virtually all AWS services for access control, including:

- Amazon S3
- Amazon EC2
- Amazon RDS
- AWS Lambda
- AWS Management Console
- AWS CLI and SDKs

## Pricing

AWS IAM is provided at no additional charge. You can create as many IAM users, groups, roles, and policies as needed for your AWS account without additional cost.