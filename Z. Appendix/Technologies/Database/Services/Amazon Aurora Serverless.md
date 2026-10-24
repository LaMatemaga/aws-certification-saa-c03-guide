---
group:
  - technology
---
Amazon Aurora Serverless is an on-demand, auto-scaling configuration for Amazon Aurora that automatically starts up, shuts down, and scales capacity based on your application's needs. It enables you to run your database in the cloud without managing database capacity, offering a cost-effective option for infrequent, intermittent, or unpredictable workloads.

## Key Features

- **Automatic scaling**: Seamlessly scales compute and memory capacity as needed.
- **Serverless architecture**: No need to provision or manage database instances.
- **Pay-per-use**: Pay only for database resources consumed.
- **Automated pausing and resuming**: Can automatically pause when not in use.
- **Rapid scaling**: Scales in fine-grained capacity increments.
- **High availability**: Maintains same availability as standard Aurora.
- **Shared storage model**: Uses Aurora's distributed storage system.
- **Connection pooling**: Built-in Aurora Serverless Data API.
- **Secure HTTP endpoint**: Access via API without managing connection pools.
- **AWS Lambda integration**: Easily connect from serverless applications.
- **Capacity planning automation**: Eliminates need for manual capacity decisions.
- **Version updates**: Managed database version updates.
- **Engine compatibility**: Available for both MySQL and PostgreSQL.
- **Capacity range configuration**: Set minimum and maximum capacity units.
- **Timeout configuration**: Customize auto-pause settings.

## Versions

- **Aurora Serverless v1**: Original version with full pause/resume capability.
    
    - MySQL 5.6/5.7 compatibility
    - PostgreSQL 10/11 compatibility
    - Scales in discrete steps
- **Aurora Serverless v2**: Newer version with enhanced performance.
    
    - MySQL 5.7/8.0 compatibility
    - PostgreSQL 11/12/13/14/15 compatibility
    - Sub-second scaling
    - Finer-grained scaling
    - Multi-AZ support
    - Global database support
    - Read replica support

## Capacity Units

- **Aurora Capacity Units (ACUs)**: The base unit of scaling.
- **v1 scaling**: Scales in discrete doubling steps (1, 2, 4, 8, 16, 32, 64, 128, 256 ACUs).
- **v2 scaling**: Scales in 0.5 ACU increments, providing finer-grained scaling.
- **Compute resources**: Each ACU includes a combination of compute and memory resources.
- **Capacity range**: Define minimum and maximum ACUs to control scaling boundaries.
- **Scaling events**: Triggered by connection count, CPU utilization, and memory usage.
- **Scaling policies**: Automatic scaling based on workload demands.

## Aurora Serverless Data API

- **HTTP endpoint access**: Connect to database without managing connections.
- **Connection pooling**: Built-in connection management.
- **AWS SDK support**: Available in multiple programming languages.
- **IAM authentication**: Control access using IAM policies.
- **Batch execution**: Run multiple SQL statements in a single API call.
- **Transaction support**: Group statements into transactions.
- **Parameter support**: Use parameters to prevent SQL injection.
- **Result set processing**: Paginate through large result sets.

## Common Use Cases

- **Variable workloads**: Applications with unpredictable traffic patterns.
- **Development and test environments**: Environments with intermittent usage.
- **New applications**: Applications with unknown or growing workloads.
- **Capacity planning challenges**: When right-sizing is difficult.
- **Multi-tenant applications**: Applications serving multiple customers.
- **Serverless applications**: Pairing with AWS Lambda and API Gateway.
- **Infrequently used applications**: Applications with hours or days between usage.
- **Microservices**: Database components of microservices architecture.
- **Batch processing**: Periodic data processing tasks.
- **Blogs and content management systems**: Varying traffic patterns.
- **Seasonal applications**: Applications with predictable busy periods.
- **Dev/test/prod environments**: Optimize costs across different environments.

## Integration with AWS Services

- **[[AWS Lambda]]**: Execute database operations from serverless functions.
- **[[Amazon API Gateway]]**: Build APIs that access the Data API.
- **[[AWS Step Functions]]**: Include database operations in workflows.
- **[[AWS AppSync]]**: Build GraphQL APIs with serverless database backend.
- **[[AWS Secrets Manager]]**: Store and rotate database credentials.
- **[[Amazon CloudWatch]]**: Monitor database metrics and logs.
- **[[AWS Identity and Access Management (IAM)]]**: Control access to database and Data API.
- **[[Amazon RDS Proxy]]**: Connection pooling for provisioned mode.
- **[[AWS Backup]]**: Managed backup solution for databases.
- **[[AWS CloudFormation]]**: Infrastructure as code deployment.

## Benefits

- **Cost optimization**: Pay only for resources used.
- **Simplified operations**: No need to manage database capacity.
- **Automated scaling**: Responds automatically to workload changes.
- **Reduced administration**: AWS handles capacity management.
- **High availability**: Built on Aurora's high-availability architecture.
- **Performance**: Same underlying performance as standard Aurora.
- **Development agility**: Focus on application development, not database management.
- **Budget predictability**: Costs align with actual usage.
- **Right-sizing automation**: System determines optimal capacity.
- **Operational resilience**: Handles unexpected traffic spikes.

## Pricing

Amazon Aurora Serverless pricing is based on:

- **Compute usage**: Pay per Aurora Capacity Unit (ACU) hour consumed.
- **Storage usage**: Pay per GB-month of storage used.
- **I/O operations**: Pay per million I/O requests.
- **Data transfer**: Standard AWS data transfer rates apply.
- **Snapshot storage**: Charge for backup storage beyond your database size.
- **Data API requests**: Pay per million requests to the Data API.

Pricing varies by region, and the service automatically scales to zero ACUs when paused (v1 only), meaning you only pay for storage during these periods.