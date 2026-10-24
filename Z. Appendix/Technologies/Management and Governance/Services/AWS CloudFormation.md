---
group:
  - technology
---
AWS CloudFormation is a service that helps you model and set up your AWS resources so you can spend less time managing those resources and more time focusing on your applications. You create a template that describes all the AWS resources you want (like EC2 instances or RDS DB instances), and CloudFormation takes care of provisioning and configuring those resources for you.

## Key Features

- **Infrastructure as Code (IaC)**: Define your infrastructure using declarative templates.
- **Template formats**: Support for JSON and YAML template formats.
- **Stacks**: Group resources as a single unit for creation, update, and deletion.
- **StackSets**: Deploy stacks across multiple accounts and regions.
- **Change sets**: Preview changes before executing them.
- **Drift detection**: Identify manual changes to your resources.
- **Designer**: Visual interface for creating and modifying templates.
- **Template validation**: Validate templates before deployment.
- **Rollback capabilities**: Automatically roll back failed deployments.
- **Custom resources**: Extend CloudFormation with custom logic.
- **Nested stacks**: Reuse common template patterns.
- **Macros**: Transform templates during deployment.
- **Resource import**: Import existing resources into CloudFormation management.
- **Template registry**: Store and share templates across your organization.
- **Stack policies**: Protect resources from unintended updates.
- **Modular templates**: Split templates into manageable components.

## Template Components

- **Resources**: AWS services and features you want to provision.
- **Parameters**: Values to pass to your template at runtime.
- **Mappings**: Key-value mappings for conditional parameter values.
- **Conditions**: Provisions resources based on conditions.
- **Outputs**: Values that can be imported into other stacks.
- **Metadata**: Additional information about the template.
- **Transform**: Specify macros that AWS CloudFormation uses to process your template.
- **Rules**: Validations performed when a stack is created or updated.

## Deployment Features

- **Stack creation**: Create a set of resources from a template.
- **Stack updates**: Modify existing resources by updating the stack.
- **Stack deletion**: Remove resources by deleting the stack.
- **Change sets**: Preview changes before applying them.
- **Resource rollback**: Automatically restore previous configuration on failure.
- **Drift detection**: Identify and fix resource drift.
- **Stack policies**: Control which resources can be updated.
- **Continuous delivery**: Integrate with CI/CD pipelines.
- **Cross-region deployments**: Deploy stacks across multiple AWS regions.
- **Cross-account deployments**: Deploy stacks across multiple AWS accounts.
- **Dynamic references**: Securely reference external values.

## Common Use Cases

- **Infrastructure provisioning**: Automate the provisioning of your AWS infrastructure.
- **Application deployment**: Deploy applications consistently across environments.
- **Disaster recovery**: Recreate infrastructure in different regions.
- **Multi-region deployments**: Deploy consistent infrastructure across regions.
- **Multi-account architectures**: Manage resources across multiple AWS accounts.
- **Landing zone setup**: Set up and configure new AWS accounts.
- **Environment standardization**: Ensure consistency across development, testing, and production.
- **Resource compliance**: Enforce infrastructure standards and compliance.
- **Blue/Green deployments**: Implement advanced deployment strategies.
- **Self-service infrastructure**: Enable developers to deploy approved templates.

## Integration with AWS Services

- **[[AWS Config]]**: Track configuration changes to your stacks.
- **[[AWS Service Catalog]]**: Create approved products using CloudFormation templates.
- **[[AWS CodePipeline]]**: Automate infrastructure deployment in CI/CD pipelines.
- **[[AWS Secrets Manager]]**: Securely access secrets during template deployment.
- **[[AWS Systems Manager Parameter Store]]**: Store and retrieve configuration data.
- **[[AWS Organizations]]**: Deploy StackSets across your organization.
- **[[AWS Identity and Access Management (IAM)]]**: Control who can access and deploy CloudFormation templates.
- **[[AWS CloudTrail]]**: Audit CloudFormation actions.

## Benefits

- **Automation**: Automate infrastructure provisioning and updates.
- **Consistency**: Deploy the same template multiple times to create identical resources.
- **Version control**: Maintain infrastructure definitions in source control.
- **Dependency management**: Automatically handle resource dependencies.
- **Time savings**: Reduce manual configuration and deployment time.
- **Documentation**: Templates serve as documentation for your infrastructure.
- **Scalability**: Easily replicate environments at scale.
- **Risk reduction**: Preview changes before applying them.
- **Cost visibility**: Estimate costs before deploying resources.
- **Compliance**: Ensure infrastructure adheres to organizational standards.

## Pricing

AWS CloudFormation is available at no additional charge. You only pay for the AWS resources that CloudFormation creates and any API calls necessary to create, update, or delete stacks.