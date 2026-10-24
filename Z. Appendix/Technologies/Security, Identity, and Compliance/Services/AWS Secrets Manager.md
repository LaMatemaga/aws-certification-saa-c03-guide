---
group:
  - technology
---
AWS Secrets Manager is a service that helps you protect access to your applications, services, and IT resources by making it easy to rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. It enables you to replace hardcoded credentials with an API call to Secrets Manager, enhancing security and simplifying compliance.

## Key Features

- **Secure secret storage**: Encrypt and store secrets with customizable access policies.
- **Automatic rotation**: Automatically rotate secrets according to schedule.
- **Built-in rotation for databases**: Native rotation for Amazon RDS, Aurora, and Redshift.
- **Custom rotation logic**: Create custom rotation functions using Lambda.
- **Fine-grained access control**: Control access with IAM policies and resource-based policies.
- **Encryption**: Secrets encrypted at rest using AWS KMS keys.
- **Monitoring and logging**: Track secret usage with CloudTrail and CloudWatch.
- **Cross-account access**: Securely share secrets across AWS accounts.
- **Cross-region replication**: Replicate secrets across AWS regions.
- **Tagging support**: Organize and track secrets with tags.
- **Secret versioning**: Maintain versions of secrets for audit and recovery.

## Secret Types

- **Database credentials**: Usernames and passwords for databases.
- **API keys**: Keys for accessing third-party services and APIs.
- **OAuth tokens**: Authentication tokens for applications.
- **SSH keys**: Keys for secure shell access.
- **TLS certificates**: Private keys and certificates.
- **PGP keys**: Encryption and signing keys.
- **Other application secrets**: Custom secrets for your applications.

## Secret Rotation

- **Scheduled rotation**: Define rotation schedules based on your requirements.
- **On-demand rotation**: Rotate secrets immediately when needed.
- **Native database rotation**: Built-in rotation for supported AWS databases.
- **Custom rotation**: Use Lambda functions for custom rotation logic.
- **Multi-user rotation**: Rotate credentials for multiple users.
- **Zero-downtime rotation**: Rotate credentials without application downtime.

## AWS Service Integrations

- **Amazon RDS**: Automatic credential rotation for RDS databases.
- **Amazon Aurora**: Automatic credential rotation for Aurora databases.
- **Amazon Redshift**: Automatic credential rotation for Redshift clusters.
- **AWS Lambda**: Custom rotation logic using Lambda functions.
- **AWS CloudFormation**: Secret creation and management through templates.
- **AWS SAM**: Secret integration in serverless applications.
- **AWS CloudTrail**: Audit logging for secret management activities.
- **AWS KMS**: Encryption key management for secrets.
- **AWS IoT**: Secure IoT device communications.

## Common Use Cases

- **Database credential management**: Securely store and rotate database credentials.
- **API key management**: Protect and manage API keys for third-party services.
- **Application secrets**: Store application configuration secrets.
- **DevOps automation**: Integrate secrets into CI/CD pipelines.
- **Compliance requirements**: Help meet compliance requirements for secret management.
- **Cross-account access**: Share secrets securely across AWS accounts.
- **Serverless applications**: Manage secrets for Lambda functions.
- **Microservices**: Distribute secrets to containerized applications.

## Benefits

- **Enhanced security**: Eliminate hardcoded secrets in application code.
- **Simplified compliance**: Meet regulatory requirements for secret rotation.
- **Reduced operational overhead**: Automate secret management tasks.
- **Centralized control**: Manage secrets from a single service.
- **Auditability**: Track secret access and changes.
- **Cost efficiency**: Pay only for the secrets you store and API calls you make.

## Pricing

AWS Secrets Manager pricing is based on:

- Number of secrets stored
- Number of API calls made to Secrets Manager
- Secret replication across regions (if used)

There are no upfront commitments, and you only pay for what you use.