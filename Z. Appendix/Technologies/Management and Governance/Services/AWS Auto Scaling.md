---
group:
  - technology
---
AWS Auto Scaling is a service that monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. It provides a unified scaling interface for multiple AWS resources, allowing you to configure scaling for individual resources or for your entire application stack.

## Key Features

- **Unified scaling interface**: Manage scaling for multiple AWS resources from a single place.
- **Application-level scaling**: Define scaling plans that span multiple resources across services.
- **Predictive scaling**: Automatically scale resources based on forecasted demand.
- **Dynamic scaling**: Adjust capacity based on real-time resource utilization.
- **Scheduled scaling**: Define scaling actions for predictable load changes.
- **Scaling strategies**: Optimize for availability, cost, or a balance between them.
- **Smart scaling recommendations**: Receive scaling recommendations based on your application's history.
- **Target tracking**: Maintain target utilization levels for your resources.
- **Step scaling**: Define scaling steps based on alarm thresholds.
- **Cooldown periods**: Prevent rapid scaling oscillations.
- **Instance maintenance policies**: Control how Auto Scaling handles instance maintenance events.
- **Lifecycle hooks**: Perform custom actions during instance launch or termination.
- **Monitoring integration**: Deep integration with [[Amazon CloudWatch]] metrics.

## Supported AWS Services

- **[[Amazon EC2]]**: Auto Scaling groups of EC2 instances.
- **[[Amazon EC2 Spot Fleets]]**: Fleets of Spot Instances.
- **[[Amazon Elastic Container Service (Amazon ECS)]]**: Container tasks and services.
- **[[Amazon Aurora]]**: Database replicas.
- **[[Amazon DynamoDB]]**: Table read and write capacity.
- **[[Amazon SageMaker]]**: Endpoint variants.
- **[[Amazon AppStream 2.0]]**: Streaming instances.
- **[[Amazon EMR]]**: Cluster core and task nodes.
- **[[Amazon Comprehend]]**: Document processing capacity.
- **[[AWS Lambda]]**: Provisioned concurrency.

## Scaling Types

- **Target tracking scaling**: Maintain a specific target value for a metric.
- **Step scaling**: Scale based on a set of scaling adjustments.
- **Scheduled scaling**: Scale based on a schedule.
- **Predictive scaling**: Scale based on load forecasts.

## Common Use Cases

- **Web applications**: Scale web servers based on traffic patterns.
- **Microservices**: Automatically scale individual services based on demand.
- **Analytics workloads**: Scale data processing resources during peak analysis times.
- **Scheduled processing**: Scale up for batch processing jobs and scale down when complete.
- **Development and testing environments**: Automatically reduce capacity during non-business hours.
- **Gaming applications**: Scale game servers based on player counts.
- **E-commerce platforms**: Handle seasonal traffic variations automatically.
- **Content delivery systems**: Scale content processing based on upload volumes.
- **Hybrid cloud environments**: Scale AWS resources to supplement on-premises capacity.

## Benefits

- **Improved application availability**: Automatically increase capacity during demand spikes.
- **Cost optimization**: Reduce capacity when not needed to minimize costs.
- **Operational efficiency**: Eliminate manual capacity planning and adjustments.
- **Application performance**: Maintain consistent performance levels.
- **Simplified management**: Manage scaling for various resources from a single interface.
- **Smarter scaling decisions**: Use predictive scaling to prepare for anticipated load increases.
- **Customizable policies**: Define scaling policies that meet your specific requirements.
- **Resource efficiency**: Optimize resource utilization across your application stack.

## Best Practices

- **Use multiple metrics**: Define scaling policies based on multiple metrics for better decisions.
- **Set appropriate cooldown periods**: Prevent scaling thrashing with suitable cooldown periods.
- **Implement gradual scaling**: Scale in smaller increments for more stable operations.
- **Enable predictive scaling**: Use historical data to scale ahead of demand.
- **Test scaling policies**: Simulate load to verify scaling policies behave as expected.
- **Configure instance protection**: Protect specific instances from scale-in actions.
- **Utilize lifecycle hooks**: Perform custom actions during scaling operations.
- **Monitor scaling activities**: Track scaling decisions and effectiveness.

## Pricing

AWS Auto Scaling is available at no additional charge. You pay only for the AWS resources that you create to run your applications and for the CloudWatch metrics used for dynamic scaling.