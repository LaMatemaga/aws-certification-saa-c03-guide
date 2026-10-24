---
group:
  - technology
---
AWS Control Tower is a service that provides a simplified way to set up and govern a secure, compliant, multi-account AWS environment. It automates the setup of a landing zone, an environment that consists of well-architected, multi-account structures following AWS best practices for security and compliance.

## Key Features

- **Landing zone creation**: Automated setup of a well-architected multi-account environment.
- **Guardrails**: Preventative and detective controls that enforce policies.
- **Account factory**: Streamlined provisioning of new AWS accounts.
- **Account enrollment**: Add existing AWS accounts to Control Tower governance.
- **Account customization**: Apply customizations to enrolled accounts.
- **Multi-account governance**: Centralized governance across multiple AWS accounts.
- **Centralized logging**: Consolidated logs across all accounts.
- **Single sign-on**: Integrated directory service for access management.
- **Compliance dashboard**: Visual indicators of policy compliance status.
- **Drift detection**: Identification of configuration deviations from the baseline.
- **Drift remediation**: Tools to bring resources back to compliant states.
- **Extension management**: Integrate with third-party solutions.
- **Cross-region support**: Deploy and manage resources across multiple AWS regions.
- **Lifecycle events**: Notifications for important Control Tower activities.

## Landing Zone Components

- **Management account**: Central administrative account for the AWS organization.
- **Log archive account**: Centralized storage for all AWS account logs.
- **Audit account**: Monitoring and compliance evaluation.
- **Member accounts**: Individual workload accounts governed by Control Tower.
- **Organizational units (OUs)**: Logical groupings of AWS accounts.
- **Service control policies (SCPs)**: Organization-level permission controls.
- **Shared networks**: Centrally managed VPCs and connectivity.
- **Identity foundation**: Centralized identity management.
- **Security baseline**: Pre-configured security settings.

## Guardrail Types

- **Mandatory guardrails**: Always-on fundamental controls that cannot be disabled.
- **Strongly recommended guardrails**: Best-practice controls that can be enabled or disabled.
- **Elective guardrails**: Optional controls for specific compliance needs.
- **Preventative guardrails**: SCPs that prevent policy violations before they occur.
- **Detective guardrails**: AWS Config rules that detect policy violations after they occur.

## Account Factory

- **Standardized account provisioning**: Consistent account creation process.
- **Account blueprints**: Templates for different types of accounts.
- **Self-service provisioning**: Allow users to provision accounts following governance standards.
- **Account customization**: Apply specific configurations to accounts.
- **Integration with AWS Service Catalog**: Managed account provisioning.
- **Account enrollment**: Bring existing accounts under Control Tower governance.
- **Account baseline**: Standard configurations applied to all accounts.
- **Account closure**: Manage the lifecycle of accounts.

## Common Use Cases

- **Cloud governance at scale**: Implement consistent governance across many accounts.
- **Compliance management**: Ensure regulatory compliance across your AWS organization.
- **Security standardization**: Apply consistent security controls.
- **Multi-team environments**: Manage environments with multiple teams and workloads.
- **Enterprise cloud adoption**: Accelerate cloud adoption with built-in best practices.
- **New AWS deployments**: Start with a well-architected environment.
- **Merger and acquisition integration**: Standardize governance across acquired AWS accounts.
- **Cloud center of excellence (CCoE)**: Establish standardized operating procedures.
- **Developer self-service**: Enable developers to provision resources within guardrails.
- **Regulatory environments**: Maintain environments for regulated industries.

## Integration with AWS Services

- **AWS Organizations**: Manage accounts and apply organization-wide policies.
- **AWS IAM Identity Center**: Provide single sign-on functionality.
- **AWS Config**: Implement detective guardrails and configuration monitoring.
- **AWS CloudTrail**: Track user activity and API usage.
- **Amazon S3**: Store logs and configuration snapshots.
- **AWS Lambda**: Automate custom operations and remediations.
- **AWS CloudFormation**: Deploy consistent resources across accounts.
- **AWS Service Catalog**: Provision standardized accounts and resources.
- **Amazon SNS**: Receive notifications about Control Tower events.
- **AWS Security Hub**: Integrate security findings into a comprehensive view.

## Benefits

- **Simplified setup**: Automate the setup of a secure, multi-account AWS environment.
- **Best practices by default**: Built-in AWS best practices for security and compliance.
- **Reduced implementation time**: Quickly establish a governed environment.
- **Consistent governance**: Apply policies uniformly across accounts.
- **Centralized visibility**: Monitor compliance from a single dashboard.
- **Automated compliance**: Automate the implementation of compliance controls.
- **Reduced operational overhead**: Standardize operations across accounts.
- **Simplified auditing**: Centralize logs and compliance information.
- **Organizational agility**: Enable teams while maintaining governance.
- **Scalable governance**: Governance model that scales with your growth.

## Pricing

AWS Control Tower is available at no additional charge. You only pay for the AWS services enabled to set up and manage your landing zone, such as AWS Config, AWS CloudTrail, and Amazon S3. These services are charged at their standard rates.