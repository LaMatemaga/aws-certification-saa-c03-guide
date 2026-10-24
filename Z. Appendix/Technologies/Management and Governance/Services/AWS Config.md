---
group:
  - technology
---
AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. It continuously monitors and records AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations.

## Key Features

- **Resource inventory**: Discover existing AWS resources and maintain an inventory.
- **Configuration history**: Record configurations over time for audit and compliance.
- **Configuration change tracking**: Monitor changes to resource configurations.
- **Configuration snapshots**: Capture point-in-time views of your AWS environment.
- **Compliance checks**: Evaluate resource configurations against best practices or custom rules.
- **Managed rules**: Pre-built compliance rules for common requirements.
- **Custom rules**: Create custom rules using AWS Lambda.
- **Conformance packs**: Deploy collections of rules and remediation actions.
- **Multi-account, multi-region data aggregation**: View configuration and compliance data across accounts and regions.
- **Configuration timeline**: View configuration changes over time.
- **Resource relationships**: Understand relationships between AWS resources.
- **Automated remediation**: Automatically fix non-compliant resources.
- **Continuous recording**: Ongoing monitoring and recording of configuration changes.
- **Advanced queries**: Search configuration properties of recorded resources.
- **Integration with other AWS services**: Work with CloudTrail, Systems Manager, Security Hub, and more.

## Supported Resource Types

AWS Config supports a wide range of AWS resource types, including:

- **Compute**: EC2 instances, Auto Scaling groups, Lambda functions
- **Storage**: S3 buckets, EBS volumes, EFS file systems
- **Database**: RDS instances, DynamoDB tables, ElastiCache clusters
- **Networking**: VPCs, subnets, security groups, route tables
- **IAM**: Users, groups, roles, policies
- **Analytics**: EMR clusters, Kinesis streams, Redshift clusters
- **Containers**: ECS clusters, EKS clusters
- **Serverless**: Lambda functions, API Gateway endpoints
- **Security**: KMS keys, WAF web ACLs, Network Firewalls
- **Management**: CloudFormation stacks, Tags, Organizations

## Rule Types

- **Managed Rules**: Over 180 pre-built rules maintained by AWS.
- **Custom Rules**: Rules created using Lambda functions or AWS Config Rule Development Kit.
- **Process Checks**: Evaluations that occur when configuration changes.
- **Periodic Checks**: Evaluations that occur at regular intervals.
- **Detective Controls**: Identify non-compliant resources after creation.
- **Preventative Controls**: Block non-compliant resources before creation (with AWS Organizations).

## Conformance Packs

- **Pre-built conformance packs**: Ready-to-deploy packs for common frameworks.
- **Custom conformance packs**: Create your own packs with specific rules.
- **Cross-account deployment**: Deploy packs across multiple accounts.
- **Compliance reporting**: Unified view of compliance across multiple rules.
- **Templated deployment**: Use YAML templates to define conformance packs.
- **Sample templates**: Pre-built templates for common compliance frameworks.

## Common Use Cases

- **Compliance auditing**: Evaluate resource configurations against internal policies or external regulations.
- **Security analysis**: Identify potential security vulnerabilities in your configurations.
- **Change management**: Track and review configuration changes over time.
- **Resource administration**: Maintain an inventory of AWS resources.
- **Operational troubleshooting**: Understand resource relationships and configurations.
- **Continuous compliance monitoring**: Ensure ongoing compliance with policies.
- **Configuration standardization**: Enforce consistent configurations across resources.
- **Drift detection**: Identify unintended or unauthorized changes to resources.
- **Governance enforcement**: Implement governance controls across your AWS environment.
- **Resource optimization**: Identify misconfigured or inefficient resources.

## Integration with AWS Services

- **AWS Security Hub**: Feed configuration compliance data into Security Hub.
- **AWS CloudTrail**: Track AWS Config API calls and configuration changes.
- **AWS Organizations**: Deploy Config rules and conformance packs across accounts.
- **AWS Systems Manager**: Implement automated remediation actions.
- **Amazon EventBridge**: Respond to configuration and compliance changes.
- **Amazon SNS**: Receive notifications about configuration changes and compliance.
- **AWS Lambda**: Create custom Config rules and remediation actions.
- **Amazon S3**: Store configuration snapshots and history data.
- **AWS Identity and Access Management**: Control access to AWS Config resources.

## Benefits

- **Continuous monitoring**: Automatically track configuration changes.
- **Comprehensive visibility**: View resource configurations and relationships.
- **Simplified compliance**: Streamline compliance auditing and reporting.
- **Configuration governance**: Enforce configuration standards across your organization.
- **Risk reduction**: Identify and remediate non-compliant resources.
- **Historical tracking**: Maintain a configuration history for audit purposes.
- **Time savings**: Automate configuration monitoring and compliance checks.
- **Improved security posture**: Identify and fix security misconfigurations.
- **Operational awareness**: Understand your AWS environment in detail.

## Pricing

AWS Config pricing is based on:

- **Configuration items**: Number of configuration items recorded
- **Config rules evaluations**: Number of rule evaluations performed
- **Conformance pack evaluations**: Number of rule evaluations within conformance packs
- **Multi-account multi-region data aggregation**: Data aggregation across accounts and regions

Pricing varies by AWS region, and a free tier is available for new customers.