---
group:
  - technology
---
Amazon Detective is a security service that makes it easy to analyze, investigate, and quickly identify the root cause of security findings or suspicious activities. Detective automatically collects log data from your AWS resources and uses machine learning, statistical analysis, and graph theory to build a linked set of data that enables you to easily conduct security investigations.

## Key Features

- **Automated data collection**: Automatically ingests and processes data from AWS CloudTrail, VPC Flow Logs, and Amazon GuardDuty.
- **Behavior graphs**: Creates behavior graphs that map the relationships between resources, IP addresses, and AWS accounts.
- **Security investigation**: Provides visualizations and context to help identify the root cause of security findings.
- **Time-based analysis**: Allows you to view how resource behaviors have changed over time.
- **Multi-account support**: Consolidate findings across AWS accounts for unified visibility.
- **Integration with GuardDuty**: Start investigations from GuardDuty findings.
- **Historical data**: Maintains up to a year of historical data for investigations.
- **Pre-built visualizations**: Provides interactive visualizations for common security investigation patterns.
- **API access**: Programmatic access to Detective data and analyses.

## Security Data Sources

- AWS CloudTrail logs
- Amazon VPC Flow Logs
- Amazon GuardDuty findings
- Amazon EKS audit logs

## Common Use Cases

- **Security findings investigation**: Quickly investigate security findings from AWS services.
- **Suspicious behavior analysis**: Identify and analyze unusual patterns of behavior.
- **Root cause analysis**: Determine the root cause of security issues.
- **Unauthorized access investigation**: Investigate instances of unauthorized resource access.
- **IP address analysis**: Analyze the activities of suspicious IP addresses.
- **Lateral movement detection**: Identify potential lateral movement within your environment.
- **Data exfiltration investigation**: Investigate potential data exfiltration attempts.
- **Post-incident analysis**: Perform detailed analysis after security incidents.

## Benefits

- **Simplified investigations**: Reduce the time and effort required to investigate security issues.
- **Automated analysis**: Machine learning automatically processes and analyzes log data.
- **Contextual insights**: View relationships between resources, users, and activities.
- **Efficient workflow**: Pre-built visualizations and guided analysis streamline investigations.
- **Reduced false positives**: Filter out normal activities to focus on potential issues.
- **Historical visibility**: Access up to a year of historical data for thorough investigations.

## Integration with AWS Services

- Amazon GuardDuty
- AWS Security Hub
- AWS CloudTrail
- Amazon VPC Flow Logs
- Amazon EKS

## Pricing

Amazon Detective pricing is based on:

- Volume of ingested log data (GB)
- Data retention period

There are no upfront commitments, and you only pay for what you use. A free trial is available for new users.