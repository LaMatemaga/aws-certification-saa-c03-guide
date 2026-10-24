---
group:
  - technology
---
Amazon GuardDuty is a threat detection service that continuously monitors for malicious activity and unauthorized behavior to protect your AWS accounts, workloads, and data. It uses machine learning, anomaly detection, and integrated threat intelligence to identify unexpected and potentially unauthorized activity within your AWS environment.

## Key Features

- **Continuous monitoring**: Analyzes AWS CloudTrail events, VPC Flow Logs, DNS logs, and other sources.
- **Threat intelligence integration**: Uses feeds from AWS and third-party sources to identify known threats.
- **Machine learning**: Employs ML to detect anomalies and potential threats.
- **Multi-account support**: Manage detection across AWS Organizations from a single account.
- **Automated response**: Trigger AWS Lambda or Amazon EventBridge in response to findings.
- **Customizable**: Set up trusted IP lists and threat lists to tune detection.
- **Multiple resource coverage**: Monitors EC2 instances, containers, S3 buckets, databases, Lambda functions, and more.
- **Findings management**: View and manage findings through console or API.
- **Integration with AWS Security Hub**: Send findings to Security Hub for centralized management.
- **Malware detection**: Identify potential malware on EC2 instances and container workloads.

## Data Sources Monitored

- **AWS CloudTrail management events**: API activity across AWS services.
- **AWS CloudTrail S3 data events**: Object-level activity within S3 buckets.
- **VPC Flow Logs**: Network traffic metadata, including rejected connections.
- **DNS logs**: DNS queries from resources within your VPCs.
- **Kubernetes audit logs**: Activity within Amazon EKS clusters.
- **RDS login activity**: Database login attempts.
- **Lambda network activity**: Network connections from Lambda functions.
- **EBS volumes**: Scan snapshots for malware.
- **Container workloads**: Runtime monitoring for container environments.

## Threat Detection Capabilities

- **Reconnaissance**: Detect port scans and unusual API calls.
- **Instance compromise**: Identify potentially compromised EC2 instances.
- **Account compromise**: Detect unauthorized access and privilege escalation.
- **Bucket compromise**: Alert on suspicious S3 activity.
- **Malicious IP addresses**: Flag connections to known malicious IPs.
- **Cryptocurrency mining**: Detect potential cryptocurrency mining activity.
- **Data exfiltration**: Identify unusual data transfer patterns.
- **Container threats**: Detect malicious behavior in container environments.
- **Malware**: Identify potential malware on EC2 instances and containers.
- **Lateral movement**: Detect potential lateral movement within your environment.

## Common Use Cases

- **Threat detection**: Identify and respond to threats across your AWS environment.
- **Security monitoring**: Continuously monitor for suspicious activity.
- **Compliance requirements**: Help meet security monitoring requirements.
- **Incident response**: Detect security incidents early in the attack lifecycle.
- **Protection against zero-day vulnerabilities**: Detect anomalous behavior that might indicate exploitation of new vulnerabilities.
- **Account takeover protection**: Monitor for signs of credential compromise.
- **Container security**: Monitor container workloads for threats.

## Benefits

- **Reduced effort**: No security infrastructure to deploy or manage.
- **Easy activation**: Enable with a few clicks in the AWS Management Console.
- **Comprehensive coverage**: Monitor multiple resource types across accounts.
- **Accurate detection**: Machine learning and integrated threat intelligence reduce false positives.
- **Cost-effective**: No upfront costs or commitments.
- **Continuous improvement**: Threat detection capabilities updated automatically.

## Pricing

Amazon GuardDuty pricing is based on:

- Volume of AWS CloudTrail events analyzed
- Volume of VPC Flow Logs and DNS logs analyzed
- Volume of data scanned for EBS volumes
- Runtime monitoring for container workloads

A 30-day free trial is available for new accounts. There are no upfront commitments, and you only pay for what you use.