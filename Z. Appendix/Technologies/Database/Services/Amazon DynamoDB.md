---
group:
  - technology
---
Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability. It is a key-value and document database that delivers single-digit millisecond performance at any scale, with built-in security, backup and restore, and in-memory caching.

## Key Features

- **Fully managed**: No servers to manage, no software to install or maintain.
- **Serverless**: Automatically scales tables to adjust for capacity and maintains performance.
- **Performance at scale**: Single-digit millisecond latency at any scale.
- **Highly available**: Data is replicated across multiple Availability Zones.
- **Flexible data model**: Supports both key-value and document data models.
- **ACID transactions**: Support for transactions across multiple items and tables.
- **Automatic scaling**: Adjust throughput capacity automatically based on traffic.
- **On-demand capacity**: Pay-per-request pricing option with no capacity planning.
- **Point-in-time recovery**: Restore tables to any point in time in the last 35 days.
- **Time to Live (TTL)**: Automatically delete expired items.
- **Global tables**: Multi-region, multi-active database with global replication.
- **Encryption at rest**: All data is encrypted by default.
- **Streams**: Capture data modification events.
- **Backups**: On-demand and continuous backups.
- **In-memory acceleration**: DynamoDB Accelerator (DAX) for microsecond response times.
- **Fine-grained access control**: Secure access to tables, items, and attributes.
- **Monitoring and metrics**: Built-in monitoring through Amazon CloudWatch.
- **Data export**: Export data to Amazon S3 for analytics and archiving.
- **Atomic counters**: Update numeric attributes atomically.
- **PartiQL support**: SQL-compatible query language.

## Data Model

- **Tables**: Collection of items with a primary key.
- **Items**: Individual data records (similar to rows).
- **Attributes**: Data elements within items (similar to columns).
- **Primary keys**:
    - **Simple primary key**: Single partition key.
    - **Composite primary key**: Partition key and sort key.
- **Secondary indexes**:
    - **Local Secondary Index (LSI)**: Same partition key as the table but different sort key.
    - **Global Secondary Index (GSI)**: Different partition and sort keys from the table.
- **Supported data types**:
    - Scalar types (string, number, binary, Boolean, null)
    - Document types (list, map)
    - Set types (string set, number set, binary set)

## Capacity Modes

- **Provisioned capacity**:
    
    - Specify read and write capacity units.
    - Use auto-scaling to adjust capacity automatically.
    - More cost-effective for predictable workloads.
    - Reserved capacity option for long-term savings.
- **On-demand capacity**:
    
    - Pay-per-request model.
    - No capacity planning needed.
    - Automatically scales up or down.
    - Best for unpredictable workloads.
    - Higher per-request cost but no risk of under or over-provisioning.

## Global Tables

- **Multi-region replication**: Replicate tables across multiple AWS regions.
- **Multi-active**: Read and write to any region.
- **Global availability**: Serve users from the closest region.
- **Disaster recovery**: Maintain access during regional outages.
- **Low-latency global access**: Provide local access for global users.
- **Conflict resolution**: Last writer wins conflict resolution strategy.

## DynamoDB Accelerator (DAX)

- **In-memory cache**: Caches frequently accessed data.
- **Microsecond performance**: Reduces response times from milliseconds to microseconds.
- **Fully managed**: No cache management required.
- **Highly available**: Multi-AZ deployment with cluster architecture.
- **Secure**: Encrypted in transit and at rest.
- **Seamless integration**: Minimal code changes to implement.
- **Write-through caching**: Maintains consistency between cache and database.

## Common Use Cases

- **Serverless web applications**: Backend database for serverless architectures.
- **Mobile backends**: Store user profiles, session data, and app state.
- **Microservices data store**: Persistent storage for microservices.
- **Gaming applications**: Track user stats, leaderboards, and game state.
- **IoT applications**: Ingest and track data from IoT devices.
- **E-commerce platforms**: Shopping carts, product catalogs, and customer profiles.
- **Real-time analytics**: Process streaming data with DynamoDB Streams.
- **Content management**: Store metadata for content distribution.
- **Social networks**: Store user relationships and activities.
- **Ad tech**: Track impressions, clicks, and conversions.
- **Session management**: Store session data for web and mobile applications.
- **Time series data**: Store metrics, logs, and sensor data with time-based sort keys.
- **Metadata storage**: Store metadata for media and files.
- **Caching layer**: Use as a distributed cache for applications.

## Integration with AWS Services

- **[[AWS Lambda]]**: Trigger functions from DynamoDB Streams.
- **[[Amazon S3]]**: Export and import data for analytics and backup.
- **[[AWS AppSync]]**: Build GraphQL APIs with DynamoDB data sources.
- **[[Amazon Kinesis]]**: Process streams for real-time analytics.
- **[[AWS Step Functions]]**: Include DynamoDB operations in workflows.
- **[[Amazon EventBridge]]**: React to DynamoDB events.
- **[[AWS Glue]]**: ETL for data integration.
- **[[Amazon Athena]]**: Query exported data in S3 using SQL.
- **[[Amazon EMR]]**: Process large datasets with Hadoop/Spark.
- **[[AWS Backup]]**: Centralized backup management.
- **[[AWS CloudFormation]]**: Infrastructure as code deployment.

## Benefits

- **Performance**: Consistently low latency at any scale.
- **Scalability**: Unlimited storage and throughput scaling.
- **Availability**: 99.999% availability SLA with multi-AZ replication.
- **Durability**: Data is highly durable with multiple copies.
- **Managed service**: No server management required.
- **Security**: Comprehensive security features.
- **Cost-effective**: Pay only for what you use.
- **Global distribution**: Deploy globally with local performance.
- **Integration**: Works seamlessly with AWS ecosystem.
- **Developer friendly**: Simple API and SDK support for many languages.

## Pricing

Amazon DynamoDB pricing is based on:

- **Provisioned capacity mode**:
    - Read and write capacity units provisioned.
    - Storage used per month.
    - Optional reserved capacity for long-term savings.
- **On-demand capacity mode**:
    - Pay per read and write request.
    - Storage used per month.
- **Additional features**:
    - Global Tables: Replicated write capacity units and data transfer.
    - Backup and restore: On-demand backup storage.
    - Streams: Read capacity units used.
    - DAX: Hourly rate per node.

There is a free tier that includes a certain amount of read and write capacity, plus storage, each month.