---
group:
  - technology
---
AWS Service Catalog is a service that enables organizations to create and manage catalogs of IT services that are approved for use on AWS. It allows administrators to create standardized products consisting of AWS resources, control who can use them, and make them available to end users who can deploy these approved resources in a self-service manner.

## Key Features

- **Product catalogs**: Create and manage catalogs of approved AWS resources.
- **Self-service provisioning**: Allow users to deploy pre-approved resources.
- **Standardized deployments**: Ensure consistent resource configurations.
- **Version control**: Maintain multiple versions of product definitions.
- **Access control**: Control who can view and launch products.
- **Delegation**: Delegate administration of portfolios.
- **Resource constraints**: Apply additional restrictions to products.
- **Tagging enforcement**: Ensure proper tagging of provisioned resources.
- **CloudFormation integration**: Use CloudFormation templates to define products.
- **Terraform integration**: Support for Terraform Cloud products.
- **Launch constraints**: Control IAM permissions for product launches.
- **Product updates**: Update provisioned products to newer versions.
- **Product sharing**: Share portfolios across accounts and organizations.
- **Budget tracking**: Associate budgets with provisioned products.
- **Integration with CI/CD pipelines**: Automated product updates.

## Core Components

- **Products**: Collections of AWS resources defined by CloudFormation templates.
- **Portfolios**: Collections of products with access controls.
- **Constraints**: Rules that control how products can be deployed.
- **Provisioned products**: Deployed instances of products.
- **Launch paths**: Routes through which end users can launch products.
- **TagOptions**: Key-value pairs that can be applied to products.
- **Service actions**: Management actions for provisioned products.
- **Product versions**: Different iterations of product definitions.
- **Template constraints**: Parameter value restrictions.
- **Stack sets**: Deploy products across multiple accounts and regions.

## Constraint Types

- **Launch constraints**: Define the IAM role used to provision resources.
- **Notification constraints**: Specify SNS topics for notifications.
- **Template constraints**: Restrict product parameters.
- **Stack set constraints**: Control deployments to multiple accounts.
- **Tag update constraints**: Control whether tags can be updated.
- **Budget constraints**: Associate AWS Budgets with provisioned products.
- **TagOptions constraints**: Apply standard tags to provisioned resources.

## Common Use Cases

- **IT service management**: Provide approved IT services to users.
- **Developer self-service**: Enable developers to provision pre-approved resources.
- **Compliance enforcement**: Ensure deployed resources meet compliance requirements.
- **Multi-account governance**: Apply consistent governance across AWS accounts.
- **Environment standardization**: Standardize development, testing, and production environments.
- **Cost control**: Manage and track AWS spending by service users.
- **Resource consistency**: Maintain consistent configurations across deployments.
- **Access management**: Control who can provision specific AWS resources.
- **Template governance**: Ensure only approved templates are used.
- **Infrastructure as code**: Implement infrastructure as code practices with governance.

## Integration with AWS Services

- **AWS CloudFormation**: Define product templates.
- **AWS Organizations**: Share portfolios across accounts.
- **AWS IAM**: Control access to products and portfolios.
- **AWS Config**: Track configuration of provisioned products.
- **AWS Budgets**: Associate budgets with provisioned products.
- **AWS CloudTrail**: Audit Service Catalog activities.
- **AWS CloudWatch**: Monitor provisioned products.
- **AWS Tags**: Tag provisioned products for organization and cost tracking.
- **AWS Systems Manager**: Automate operational tasks for provisioned products.
- **Terraform Cloud**: Support for Terraform-defined products.

## Benefits

- **Governance enforcement**: Ensure compliance with organizational policies.
- **Self-service capabilities**: Enable users to provision approved resources.
- **Standardization**: Maintain consistent deployment patterns.
- **Reduced admin burden**: Delegate provisioning while maintaining control.
- **Cost management**: Control and track AWS spending.
- **Version control**: Manage and upgrade resource configurations.
- **Simplified compliance**: Enforce compliance requirements consistently.
- **Faster deployment**: Accelerate resource provisioning.
- **Reduced errors**: Eliminate manual configuration errors.
- **Centralized management**: Manage products from a central location.

## Pricing

AWS Service Catalog is available at no additional charge. You only pay for the AWS resources that are provisioned through Service Catalog based on the standard pricing for those services.