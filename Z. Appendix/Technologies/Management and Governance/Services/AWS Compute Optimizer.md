---
group:
  - technology
---
AWS Compute Optimizer is a service that analyzes the configuration and utilization metrics of your AWS resources to provide recommendations that can help you reduce costs and improve performance. It uses machine learning to recommend optimal AWS resources for your workloads, helping you right-size your infrastructure to match your application needs.

## Key Features

- **Resource recommendations**: Get optimization recommendations for various AWS compute resources.
- **Machine learning-based analysis**: Uses ML to identify patterns and make optimized recommendations.
- **Utilization metrics analysis**: Analyzes actual resource utilization over time.
- **Savings opportunity estimates**: See estimated monthly savings for each recommendation.
- **Performance risk assessment**: Understand potential performance impact of recommendations.
- **External metrics integration**: Incorporate external metrics for better recommendations.
- **Recommendation export**: Export recommendations to CSV for further analysis.
- **AWS Organizations integration**: View recommendations across your organization.
- **Recommendation preferences**: Customize recommendations based on your requirements.
- **Resource right-sizing**: Identify over-provisioned and under-provisioned resources.
- **Detail-level insights**: View detailed analysis of each recommendation.
- **Multi-account support**: Analyze resources across multiple accounts.
- **Savings plans and Reserved Instances recommendations**: Optimize commitment-based discount models.

## Supported Resources

- **Amazon EC2 instances**: Right-size instances based on workload characteristics.
- **Amazon EC2 Auto Scaling groups**: Optimize instance types in Auto Scaling groups.
- **AWS Lambda functions**: Adjust memory configurations for optimal performance and cost.
- **Amazon EBS volumes**: Right-size EBS volumes based on actual usage.
- **Amazon RDS instances**: Optimize database instance types and configurations.
- **Amazon SageMaker instances**: Right-size SageMaker endpoint instances.
- **Amazon ECS services on Fargate**: Optimize CPU and memory configurations.

## Recommendation Types

- **Instance type recommendations**: Suggestions for more appropriate EC2 instance types.
- **Auto Scaling group recommendations**: Optimized instance types for Auto Scaling groups.
- **EBS volume recommendations**: Right-sized EBS volume types and sizes.
- **Lambda function memory recommendations**: Optimal memory settings for Lambda functions.
- **Over-provisioned resource identification**: Resources with consistently low utilization.
- **Under-provisioned resource identification**: Resources with potential performance constraints.
- **Savings plans recommendations**: Suggestions for commitment-based discount purchases.
- **Reserved Instance recommendations**: Guidance on RI purchases.

## Common Use Cases

- **Cost optimization**: Reduce AWS spending by right-sizing resources.
- **Performance improvement**: Enhance application performance with properly sized resources.
- **Infrastructure planning**: Make informed decisions for future deployments.
- **Cloud governance**: Enforce efficient resource utilization.
- **FinOps implementation**: Support financial operations in the cloud.
- **Operational excellence**: Maintain optimal infrastructure configurations.
- **Migration planning**: Size resources correctly when migrating to AWS.
- **Continuous optimization**: Regularly adapt resources to changing workloads.
- **Budget management**: Control and predict cloud spending.
- **Sustainability improvement**: Reduce carbon footprint by eliminating over-provisioning.

## Integration with AWS Services

- **AWS Organizations**: Analyze resources across your organization.
- **AWS Cost Explorer**: View cost implications of recommendations.
- **AWS Trusted Advisor**: Complement other cost optimization checks.
- **AWS CloudWatch**: Use performance metrics to inform recommendations.
- **AWS Management Console**: Access recommendations through a unified interface.
- **AWS Cost and Usage Report**: Detailed cost data for better recommendations.
- **AWS Budgets**: Set and manage cost targets.
- **AWS Resource Groups**: Organize and manage resources efficiently.

## Benefits

- **Cost reduction**: Identify and eliminate resource waste.
- **Performance optimization**: Ensure resources meet application requirements.
- **Data-driven decisions**: Make resource changes based on actual usage data.
- **Reduced management overhead**: Automated analysis instead of manual review.
- **Continuous improvement**: Ongoing recommendations as workloads change.
- **Simplified right-sizing**: Clear recommendations with projected impact.
- **Organization-wide insights**: Optimize resources across your entire AWS organization.
- **Enhanced forecasting**: Better predict future resource needs and costs.
- **Sustainability**: Reduce environmental impact through efficient resource use.

## Pricing

AWS Compute Optimizer is available at no additional charge for basic recommendations. Enhanced infrastructure metrics for more accurate recommendations are available for an additional fee. You only pay for the AWS resources you create and use, based on the standard pricing for those services.