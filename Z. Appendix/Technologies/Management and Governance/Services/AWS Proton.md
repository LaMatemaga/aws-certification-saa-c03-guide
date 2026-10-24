---
group:
  - technology
---
AWS Proton is a fully managed delivery service for container and serverless applications. It helps platform teams define standardized infrastructure and deployment tooling for developers, while giving developers an easy, self-service way to provision their application infrastructure using those approved standards.

## Key Features

- **Template libraries**: Create and manage standardized infrastructure templates.
- **Self-service provisioning**: Allow developers to deploy using approved templates.
- **Infrastructure as code**: Define infrastructure using CloudFormation or Terraform.
- **Multi-account deployments**: Deploy across multiple AWS accounts.
- **CI/CD pipelines**: Automated provisioning of CI/CD pipelines.
- **Template versioning**: Manage different versions of infrastructure templates.
- **Automated deployments**: Automatically deploy applications and infrastructure.
- **Change management**: Track and manage infrastructure changes.
- **Template composition**: Build complex environments from reusable components.
- **Environment management**: Create and manage deployment environments.
- **Customizable inputs**: Allow customization within defined parameters.
- **Infrastructure drift detection**: Identify manual changes to provisioned resources.
- **Monitoring integration**: Connect with monitoring and observability tools.
- **Event notifications**: Notifications for template and deployment events.
- **AWS service integration**: Built-in integration with AWS deployment services.

## Components

- **Templates**: Define standardized infrastructure patterns.
  - **Environment templates**: Define shared infrastructure (VPC, ECS clusters, etc.).
  - **Service templates**: Define service-specific infrastructure (ECS services, Lambda functions, etc.).
  - **Component templates**: Define reusable infrastructure components.

- **Environments**: Deployment targets for applications.
  - **Production environments**: For production workloads.
  - **Development environments**: For development and testing.
  - **Shared environments**: Common infrastructure used by multiple services.
  - **Environment accounts**: AWS accounts hosting environments.

- **Services**: Application workloads deployed using templates.
  - **Service instances**: Deployed instances of a service.
  - **Service pipelines**: CI/CD pipelines for services.
  - **Service components**: Modular parts of a service.
  - **Service configurations**: Service-specific settings.

## Template Types

- **Environment templates**: Define shared resources like networking, security, and monitoring.
- **Service templates**: Define application-specific resources and pipelines.
- **Component templates**: Define reusable infrastructure components.
- **Pipeline templates**: Define CI/CD pipeline configurations.
- **CloudFormation templates**: Use AWS CloudFormation to define infrastructure.
- **Terraform templates**: Use HashiCorp Terraform to define infrastructure.

## Common Use Cases

- **Platform engineering**: Create standardized infrastructure for development teams.
- **Developer self-service**: Enable developers to provision approved infrastructure.
- **Microservices deployment**: Standardize microservice deployment patterns.
- **Multi-account management**: Manage deployments across multiple AWS accounts.
- **Container orchestration**: Standardize container deployment environments.
- **Serverless applications**: Define consistent serverless application patterns.
- **Infrastructure governance**: Enforce standards for cloud infrastructure.
- **DevOps automation**: Automate infrastructure and application deployment.
- **Environment consistency**: Ensure consistency across development, testing, and production.
- **Compliance enforcement**: Embed compliance requirements into infrastructure templates.

## Integration with AWS Services

- **AWS CloudFormation**: Define infrastructure templates.
- **HashiCorp Terraform**: Alternative IaC integration.
- **AWS CodeBuild**: Build application code.
- **AWS CodePipeline**: Set up continuous delivery pipelines.
- **AWS CodeDeploy**: Deploy applications to compute platforms.
- **AWS CodeStar Connections**: Connect to source code repositories.
- **AWS IAM**: Manage access to Proton resources.
- **AWS Organizations**: Deploy across multiple accounts.
- **AWS CloudWatch**: Monitor provisioned resources.
- **AWS EventBridge**: React to Proton events.

## Benefits

- **Developer productivity**: Simplify infrastructure provisioning for developers.
- **Standardization**: Enforce consistent infrastructure patterns.
- **Reduced toil**: Automate repetitive provisioning tasks.
- **Governance and compliance**: Ensure infrastructure meets company standards.
- **Operational consistency**: Maintain consistent deployment patterns.
- **Scalable management**: Manage infrastructure at scale.
- **Faster delivery**: Accelerate application deployment.
- **Reduced complexity**: Simplify infrastructure management.
- **Better collaboration**: Improve collaboration between platform and application teams.
- **Controlled customization**: Allow flexibility within defined guardrails.

## Pricing

AWS Proton pricing is based on:
- **Environment templates**: Monthly charge per registered template.
- **Service templates**: Monthly charge per registered template.
- **Environment deployments**: Charge per environment deployment.
- **Service deployments**: Charge per service deployment.

You also pay for the underlying AWS resources that are provisioned by Proton templates. There are no upfront commitments, and pricing varies by region.