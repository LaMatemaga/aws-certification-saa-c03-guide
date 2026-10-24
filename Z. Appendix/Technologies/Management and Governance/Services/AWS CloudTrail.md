---
group:
  - technology
---
AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. It records and logs AWS API calls for your account, providing you with a history of AWS API calls for security analysis, resource change tracking, and compliance auditing.

## Key Features

- **API activity logging**: Record API calls made within your AWS account.
- **Event history**: 90-day viewable history of account activity without additional configuration.
- **Management events**: Log control plane operations on your AWS resources.
- **Data events**: Log data plane operations on your AWS resources.
- **Network activity events**: Log AWS API calls that transit through VPC endpoints.
- **Insights events**: Identify unusual API activity in your AWS account.
- **Multi-region trails**: Collect API activity from all AWS regions.
- **Multi-account trails**: Consolidate logs from multiple AWS accounts.
- **Event data stores**: Long-term, immutable storage for CloudTrail events.
- **Log file validation**: Verify that logs haven't been tampered with.
- **Log file encryption**: Encrypt log files using AWS KMS keys.
- **Real-time monitoring**: Stream events to Amazon CloudWatch Logs.
- **Integration with EventBridge**: Trigger automated responses to specific API activities.
- **Lake integration**: Query and analyze events using CloudTrail Lake.
- **Resource-based data sources**: Capture events from specific AWS resources.
- **Organization trails**: Manage trails for all accounts in an AWS Organization.

## Event Types

- **Management events**: Control plane operations that modify AWS resources.
- **Data events**: Data plane operations on resources (e.g., S3 object-level operations).
- **Insights events**: Unusual API activity patterns detected by CloudTrail.
- **Network activity events**: VPC service endpoint activity.
- **Non-API events**: Activity that doesn't occur through AWS APIs (e.g., console sign-ins).

## CloudTrail Lake Features

- **SQL-based event queries**: Search and analyze events using SQL.
- **Event data stores**: Purpose-built storage optimized for high-performance queries.
- **Federated queries**: Query across multiple event data stores.
- **Dashboard integrations**: Visualize event data in Amazon Athena and QuickSight.
- **Channel integrations**: Ingest events from non-AWS sources.
- **Extended retention**: Store events for up to 7 years.

## Common Use Cases

- **Security analysis**: Identify potential security incidents.
- **Resource change tracking**: Monitor changes to AWS resources.
- **Compliance auditing**: Maintain records for regulatory compliance.
- **Operational troubleshooting**: Diagnose operational issues.
- **DevOps monitoring**: Track API calls made by development tools.
- **User activity monitoring**: Review actions taken by IAM users and roles.
- **API usage patterns**: Understand how AWS services are being used.
- **Billing verification**: Verify resource creation and deletion.
- **Forensic investigations**: Investigate security incidents.
- **Cross-account management**: Monitor activity across multiple accounts.

## Integration with AWS Services

- **Amazon S3**: Store log files in S3 buckets.
- **Amazon CloudWatch Logs**: Stream logs for real-time monitoring.
- **Amazon EventBridge**: Trigger automated responses to API events.
- **AWS Lambda**: Process log data automatically.
- **Amazon Athena**: Query log data using standard SQL.
- **Amazon QuickSight**: Create visualizations of CloudTrail data.
- **AWS Organizations**: Configure organization-wide trails.
- **AWS Security Hub**: Correlate findings with CloudTrail events.
- **Amazon Detective**: Investigate security issues using CloudTrail data.
- **AWS Key Management Service**: Encrypt log files.

## Benefits

- **Security and compliance**: Maintain an immutable audit trail of account activity.
- **Visibility**: Comprehensive view of actions taken in your AWS account.
- **Detective controls**: Identify unusual or unauthorized activity.
- **Operational health**: Troubleshoot operational issues.
- **Accountability**: Track user actions and resource changes.
- **Risk management**: Detect and respond to inappropriate configurations.
- **Regulatory adherence**: Meet regulatory requirements for audit trails.
- **Simplified audits**: Provide necessary evidence for external auditors.
- **Cross-account monitoring**: Centralize monitoring for multi-account environments.

## Pricing

AWS CloudTrail pricing is based on:
- **Trails**: Management events are free; data, Insights, and network events have associated costs
- **CloudTrail Lake**: Charges for event ingestion and storage
- **Event data stores**: Costs vary based on retention period
- **Queries**: Pay for the amount of data scanned during queries

Additional charges may apply for related services like Amazon S3 storage, KMS encryption, and CloudWatch Logs.