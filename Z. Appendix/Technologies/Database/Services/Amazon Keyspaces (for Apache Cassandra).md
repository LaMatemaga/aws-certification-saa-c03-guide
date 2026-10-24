---
group:
  - technology
---
Amazon Keyspaces is a scalable, highly available, and managed Apache Cassandra-compatible database service. It allows you to use the same Cassandra Query Language (CQL) code, drivers, and tools that you use with Apache Cassandra while benefiting from the managed service capabilities of AWS.

## Key Features

- **Cassandra compatibility**: Compatible with Apache Cassandra 3.11.2 API.
- **Serverless architecture**: No cluster management or server provisioning required.
- **Automatic scaling**: Scales tables up and down automatically.
- **High availability**: Replicates data across multiple AWS Availability Zones.
- **Pay-per-use pricing**: Pay only for the resources you use.
- **On-demand capacity mode**: Pay for reads and writes you perform, without capacity planning.
- **Provisioned capacity mode**: Specify and adjust capacity for predictable workloads.
- **Auto-scaling**: Automatically adjust provisioned capacity based on usage.
- **Point-in-time recovery**: Restore to any point within the last 35 days.
- **Continuous backup**: Data is continuously backed up with no performance impact.
- **Encryption at rest**: All data is encrypted by default.
- **Encryption in transit**: Data is encrypted in transit with TLS.
- **VPC endpoints**: Private access using AWS PrivateLink.
- **Multi-region access**: Access tables from different AWS regions.
- **Monitoring and metrics**: Integration with Amazon CloudWatch.
- **CQL operations**: Support for Cassandra Query Language operations.
- **Multi-row transactions**: Support for lightweight transactions.
- **Time-to-live (TTL)**: Automatically expire data after a specified time.
- **IAM integration**: Fine-grained access control with AWS IAM.

## Data Model

- **Keyspaces**: Top-level containers for tables (similar to schemas).
- **Tables**: Collections of rows of data.
- **Partitions**: Groupings of rows that share the same partition key.
- **Primary keys**:
    - **Partition key**: Determines data distribution.
    - **Clustering columns**: Defines sort order within a partition.
- **Columns**: Individual data elements.
- **Supported data types**:
    - Primitive types (text, int, bigint, float, double, boolean, etc.)
    - Collection types (list, map, set)
    - Other types (uuid, timeuuid, timestamp, blob, etc.)

## Cassandra Compatibility

- **CQL support**: Compatible with Cassandra Query Language.
- **Standard drivers**: Works with existing Cassandra drivers.
- **Driver authentication**: Support for SigV4 authentication plugin.
- **Consistency levels**: Support for LOCAL_QUORUM and LOCAL_ONE.
- **Secondary indexes**: Support for secondary indexes on non-primary key columns.
- **Materialized views**: Support for materialized views.
- **Batch operations**: Support for batched writes.
- **TTL and Writetime**: Support for time-to-live and timestamp functionality.
- **Static columns**: Support for static columns in table definitions.
- **Query operators**: Support for Cassandra query operators.
- **User-defined types**: Support for complex data structures.
- **Counter data type**: Support for counter columns.

## Capacity Modes

- **On-demand capacity mode**:
    
    - Pay-per-request pricing.
    - No capacity planning required.
    - Automatically scales to handle traffic fluctuations.
    - Best for unpredictable workloads.
- **Provisioned capacity mode**:
    
    - Specify read and write capacity units.
    - More cost-effective for predictable workloads.
    - Auto-scaling capability to adjust capacity automatically.

## Common Use Cases

- **IoT applications**: Store and query time-series data from IoT devices.
- **User profile management**: Store and retrieve user profiles with varying attributes.
- **Product catalogs**: Manage product data with complex schemas.
- **High-scale industrial applications**: Handle heavy write workloads.
- **Content management systems**: Store and retrieve content metadata.
- **Real-time analytics**: Process and analyze time-series data.
- **Personalization systems**: Store customer preferences and behaviors.
- **Time series data**: Track metrics, events, and sensor data.
- **Mobile application backends**: Backend storage for mobile applications.
- **Cassandra migrations**: Move from self-managed Cassandra to a managed service.
- **Event logging and monitoring**: Capture and query system events.
- **Messaging platforms**: Store message data and metadata.
- **Gaming applications**: Store game state and player data.
- **E-commerce applications**: Manage shopping carts and order information.

## Integration with AWS Services

- **[[AWS Identity and Access Management (IAM)]]**: Authentication and authorization.
- **[[Amazon VPC]]**: Network isolation and security.
- **[[AWS CloudTrail]]**: Audit API calls and usage.
- **[[Amazon CloudWatch]]**: Monitor performance metrics and alarms.
- **[[AWS Glue]]**: ETL for data integration.
- **[[Amazon EMR]]**: Big data processing integration.
- **[[AWS Lambda]]**: Serverless application integration.
- **[[AWS Backup]]**: Centralized backup management.
- **[[AWS CloudFormation]]**: Infrastructure as code deployment.
- **[[AWS Secrets Manager]]**: Store and manage connection credentials.
- **[[AWS CodePipeline]]**: CI/CD integration for database schema changes.

## Benefits

- **Operational simplicity**: No servers or clusters to manage.
- **Scalability**: Seamlessly scale to handle any workload.
- **Availability**: High availability with multi-AZ replication.
- **Performance**: Consistent, single-digit millisecond performance.
- **Security**: Comprehensive security features.
- **Compatibility**: Use existing Cassandra code and tools.
- **Cost-effectiveness**: Pay only for what you use.
- **Managed service**: AWS handles infrastructure management.
- **Migration path**: Easy migration from self-managed Cassandra.
- **Hybrid capabilities**: Mix with existing Cassandra clusters.
- **Developer productivity**: Focus on application, not database management.

## Pricing

Amazon Keyspaces pricing is based on:

- **Storage**: Pay per GB of data stored per month.
- **Read/Write throughput**: Pay based on your capacity mode:
    - On-demand: Pay per read and write request unit.
    - Provisioned: Pay for provisioned read and write capacity units.
- **Backup storage**: Pay for storage used for point-in-time recovery beyond your table size.
- **Data transfer**: Standard AWS data transfer rates apply.

There is a free tier for new customers that includes a certain amount of read/write capacity, storage, and data transfer each month.