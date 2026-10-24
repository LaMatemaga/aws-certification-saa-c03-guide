---
group:
  - technology
---
AWS Systems Manager is a management service that helps you automatically collect software inventory, apply OS patches, create system images, and configure Windows and Linux operating systems. These capabilities help you define and track system configurations, prevent drift, and maintain software compliance of your EC2 and on-premises configurations.

## Key Capabilities

### Operations Management

- **Explorer**: Cross-account, cross-region operational dashboard.
- **OpsCenter**: View, investigate, and resolve operational issues.
- **Incident Manager**: Manage incidents and outages.
- **CloudWatch Dashboards**: Create and view custom dashboards.
- **Personal Health Dashboard**: View AWS service health events.
- **Trusted Advisor**: AWS best practice recommendations.

### Application Management

- **Application Manager**: Manage resources grouped by application.
- **AppConfig**: Configure, validate, and deploy application configurations.
- **Parameter Store**: Store configuration data and secrets.
- **Systems Manager for SAP**: Manage SAP applications.
- **Application Insights**: Monitor application health.

### Change Management

- **Change Manager**: Request, approve, and implement operational changes.
- **Automation**: Automate operational tasks across resources.
- **Change Calendar**: Track and manage change events.
- **Maintenance Windows**: Define schedules for performing actions.

### Node Management

- **Fleet Manager**: Remotely manage nodes at scale.
- **Compliance**: Scan managed nodes for patch and configuration compliance.
- **Inventory**: Collect metadata from managed nodes.
- **Hybrid Activations**: Manage on-premises servers and VMs.
- **Session Manager**: Securely connect to instances without SSH/RDP.
- **Run Command**: Run commands across multiple instances.
- **State Manager**: Define and maintain consistent configurations.
- **Patch Manager**: Automate patching processes.
- **Distributor**: Create and deploy packages.

### Quick Setup

- **Resource Discovery**: Find resources to manage.
- **Quick Setup**: Quickly configure common operational tasks.
- **CloudFormation Templates**: Deploy using infrastructure as code.

## Key Features

- **Cross-platform support**: Manage Windows and Linux systems.
- **Hybrid environment management**: Support for EC2 instances, on-premises servers, and VMs.
- **Secure automation**: Run automation with specific IAM roles.
- **Parameter hierarchies**: Organize parameters in hierarchical structures.
- **Integration with other AWS services**: Work with services like CloudWatch, IAM, and CloudFormation.
- **API and CLI access**: Programmatic access to all functionality.
- **Resource grouping**: Group resources for management.
- **Compliance reporting**: Track compliance status.
- **Operational dashboards**: Visualize operational data.
- **Runbook sharing**: Share automation documents.
- **Custom approval workflows**: Define approval processes for changes.
- **Secure connections**: Connect to instances without exposing ports.
- **Document versioning**: Maintain versions of automation documents.
- **Maintenance window scheduling**: Define when actions can be performed.

## Common Use Cases

- **Infrastructure automation**: Automate operational tasks at scale.
- **Patch management**: Automate OS and application patching.
- **Configuration management**: Maintain consistent configurations.
- **Resource compliance**: Ensure resources comply with policies.
- **Secure instance access**: Connect to instances without SSH/RDP.
- **Operational insights**: Gain visibility into operations.
- **Incident management**: Respond to and resolve incidents efficiently.
- **Change control**: Manage operational changes safely.
- **Application configuration**: Manage application configurations.
- **Hybrid infrastructure management**: Manage AWS and on-premises resources.

## Integration with AWS Services

- **Amazon EC2**: Manage EC2 instances.
- **AWS CloudWatch**: Collect and monitor metrics.
- **AWS CloudTrail**: Audit Systems Manager activities.
- **AWS Config**: Track configuration changes.
- **AWS Organizations**: Manage across accounts.
- **AWS Secrets Manager**: Store and retrieve secrets.
- **AWS Identity and Access Management**: Control access to resources.
- **AWS Lambda**: Trigger automation based on events.
- **AWS Step Functions**: Orchestrate complex workflows.
- **AWS Backup**: Manage backup policies.
- **AWS Security Hub**: Connect security findings with operational data.
- **AWS Marketplace**: Deploy Marketplace products.

## Benefits

- **Operational efficiency**: Automate repetitive tasks and reduce manual effort.
- **Improved security**: Secure access to instances and management of configurations.
- **Reduced downtime**: Proactively manage changes and resolve incidents faster.
- **Consistent configurations**: Prevent configuration drift across your environment.
- **Cost optimization**: Identify and address operational inefficiencies.
- **Increased visibility**: Get a comprehensive view of your infrastructure.
- **Simplified compliance**: Enforce compliance with policies and regulations.
- **Scalable management**: Manage resources at scale as your environment grows.
- **Reduced operational risk**: Implement safe change processes.
- **Centralized operations**: Manage all operations from a single service.

## Pricing

AWS Systems Manager pricing varies by feature:

- **Core features**: Many features are available at no additional charge.
- **Advanced features**: Some features like Parameter Store advanced parameters have usage-based charges.
- **OpsCenter and Explorer**: Per-resource charges for cross-account/cross-region management.
- **Session Manager**: Charges for session data stored in S3 or CloudWatch Logs.
- **Automation**: Charges for automation execution time.
- **Change Manager**: Charges for change templates and requests.

Standard AWS data transfer and storage charges apply. Pricing varies by region, and specific feature usage determines your actual cost.