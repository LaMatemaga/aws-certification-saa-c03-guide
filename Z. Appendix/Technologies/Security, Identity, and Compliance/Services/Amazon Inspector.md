---
group:
  - technology
---
Amazon Inspector is an automated vulnerability management service that continually scans AWS workloads for software vulnerabilities and unintended network exposure. It helps you meet security and compliance requirements by automating security assessments for your Amazon EC2 instances, container images in Amazon ECR, and Lambda functions.

## Key Features

- **Automated vulnerability scanning**: Continuously scans for vulnerabilities in EC2 instances, container images, and Lambda functions.
- **Network reachability analysis**: Identifies unintended network paths to resources.
- **Risk scoring**: Assigns risk scores based on vulnerability severity and exploitability.
- **Contextual risk assessment**: Considers network accessibility when determining risk.
- **Automated resource discovery**: Automatically discovers eligible resources for scanning.
- **Multi-account support**: Manage vulnerability assessments across AWS Organizations.
- **Vulnerability intelligence database**: Draws from multiple sources including CVE database.
- **Integration with AWS Security Hub**: Send findings to Security Hub for centralized management.
- **Amazon EventBridge integration**: Trigger automated workflows based on findings.
- **API access**: Programmatic access to findings and assessment data.

## Scan Types

- **EC2 scanning**:
    - Software vulnerabilities in EC2 instances
    - Network reachability assessment
    - Agent-less scanning
- **Container scanning**:
    - Software vulnerabilities in container images in Amazon ECR
    - Scan images when pushed and continuously
- **Lambda function scanning**:
    - Software vulnerabilities in Lambda function code and layers
    - Scan when deployed and continuously

## Vulnerability Management

- **Continuous scanning**: Resources are scanned continuously for vulnerabilities.
- **Risk prioritization**: Vulnerabilities are prioritized based on severity, exploitability, and accessibility.
- **Exploit availability**: Information on whether exploit code is publicly available.
- **Patch information**: Details on available patches and remediation steps.
- **Contextual information**: Additional context for better understanding of risks.

## Common Use Cases

- **Vulnerability management**: Continuously scan for and remediate vulnerabilities.
- **Compliance requirements**: Meet security scanning requirements for compliance frameworks.
- **Security assessment**: Assess the security posture of your AWS workloads.
- **DevSecOps integration**: Integrate security scanning into CI/CD pipelines.
- **Runtime monitoring**: Monitor running workloads for new vulnerabilities.
- **Network configuration validation**: Validate network configurations and identify exposures.
- **Container security**: Scan container images for vulnerabilities before deployment.
- **Serverless security**: Identify vulnerabilities in Lambda functions.

## Benefits

- **Reduced effort**: No security infrastructure to deploy or manage.
- **Comprehensive coverage**: Coverage for multiple resource types.
- **Continuous monitoring**: Ongoing assessment rather than point-in-time scans.
- **Contextual risk assessment**: Risk prioritization based on multiple factors.
- **Integration with AWS services**: Seamless integration with other AWS security services.
- **Centralized management**: Manage assessments across multiple accounts.

## Pricing

Amazon Inspector pricing is based on:

- Number of EC2 instances scanned
- Number of container images scanned
- Number of Lambda functions scanned

A 15-day free trial is available for new accounts. There are no upfront commitments, and you only pay for what you use.