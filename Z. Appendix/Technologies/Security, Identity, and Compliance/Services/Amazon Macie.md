---
group:
  - technology
---
Amazon Macie is a fully managed data security and data privacy service that uses machine learning and pattern matching to discover and protect your sensitive data in AWS. Macie automatically discovers sensitive data such as personally identifiable information (PII) or financial data, provides visibility of data security risks, and enables automated protection against those risks.

## Key Features

- **Automated sensitive data discovery**: Continuously identify sensitive data across your Amazon S3 buckets.
- **Data classification**: Classify data using built-in and custom data identifiers.
- **Risk assessment**: Evaluate S3 bucket security and privacy settings.
- **Findings management**: View and manage findings through console or API.
- **Integration with AWS Security Hub**: Send findings to Security Hub for centralized management.
- **Multi-account support**: Manage data security across AWS Organizations from a single account.
- **Custom data identifiers**: Create custom patterns to identify organization-specific sensitive data.
- **Automated remediation**: Trigger AWS Lambda or Amazon EventBridge in response to findings.
- **Comprehensive coverage**: Analyze a wide range of file types including documents, spreadsheets, images, and compressed archives.

## Data Types Identified

Macie provides built-in detectors for many types of sensitive data, including:

- **Financial information**: Credit card numbers, bank account numbers, financial instruments.
- **Personal information**: Names, addresses, phone numbers, birth dates, national identification numbers.
- **Credentials**: API keys, private keys, passwords.
- **Healthcare information**: Medical record numbers, health insurance information, medical procedures.
- **Custom information**: Define your own sensitive data patterns.

## Discovery Methods

- **Automated sensitive data discovery**: Continuous, account-level discovery of sensitive data.
- **Sensitive data discovery jobs**: On-demand or scheduled jobs to analyze specific S3 buckets.
- **Bucket security evaluation**: Ongoing analysis of S3 bucket security and access controls.

## Common Use Cases

- **Data security**: Discover and protect sensitive data stored in S3.
- **Compliance requirements**: Help meet compliance requirements for data security.
- **Data visibility**: Understand what sensitive data you have and where it's stored.
- **Risk assessment**: Identify security risks in your data storage.
- **Data breach prevention**: Identify potential data exposures before they become breaches.
- **Third-party data risk management**: Identify sensitive data shared with third parties.
- **Data minimization**: Identify and remove unnecessary sensitive data.
- **Cloud migration**: Discover sensitive data before migrating to the cloud.

## Benefits

- **Reduced manual effort**: Automate sensitive data discovery and classification.
- **Comprehensive coverage**: Identify sensitive data across your S3 environment.
- **Proactive protection**: Identify security risks before they lead to data breaches.
- **Scalability**: Scale data security alongside your cloud storage.
- **Integration**: Seamless integration with other AWS security services.
- **Customization**: Define specific patterns to match your organization's needs.

## Integration with AWS Services

- AWS Security Hub
- Amazon EventBridge
- AWS Organizations
- AWS CloudTrail
- AWS Lambda

## Pricing

Amazon Macie pricing is based on:

- Number of S3 buckets evaluated for security and access controls
- Volume of data processed for sensitive data discovery
- Volume of sensitive data discovered and monitored

A 30-day free trial is available for new accounts. There are no upfront commitments, and you only pay for what you use.****