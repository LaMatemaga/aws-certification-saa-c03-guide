---
group:
  - technology
---
Amazon ElastiCache is a fully managed in-memory caching service that makes it easy to deploy, operate, and scale an in-memory cache in the cloud. It improves the performance of web applications by allowing you to retrieve information from fast, managed, in-memory caches, instead of relying entirely on slower disk-based databases.

## Key Features

- **Fully managed**: AWS handles administration, maintenance, and patching.
- **Two caching engines**: Redis and Memcached.
- **Scalability**: Scale out horizontally and vertically to match demand.
- **High availability**: Automatic failover and Multi-AZ support (Redis).
- **Performance**: Sub-millisecond response times.
- **Data persistence**: Options to persist data to disk (Redis).
- **Data encryption**: Encryption at rest and in transit.
- **Backup and restore**: Automated backups with point-in-time recovery (Redis).
- **Auto-discovery**: Clients automatically discover cache nodes.
- **Monitoring**: Integration with CloudWatch for metrics and alarms.
- **Parameter groups**: Customize cache engine parameters.
- **Maintenance windows**: Control when software updates occur.
- **Engine-specific features**: Support for Redis and Memcached specific capabilities.
- **Global datastores**: Cross-region replication (Redis).
- **Data tiering**: Store data across memory and SSD (Redis).
- **Serverless option**: Auto-scaling capacity with no cluster management (Redis).

## Engine Choices

### Redis

- **Rich data structures**: Strings, lists, sets, sorted sets, hashes, bitmaps, etc.
- **High availability**: Primary/replica architecture with automatic failover.
- **Persistence**: Optional RDB and AOF persistence.
- **Transaction support**: Multi-operation transactions.
- **Pub/Sub messaging**: Built-in publish/subscribe functionality.
- **Lua scripting**: Server-side scripting.
- **Geospatial support**: Store and query geospatial data.
- **Redis Cluster**: Horizontal scaling with data sharding.
- **Redis AUTH**: Password protection.
- **Redis Streams**: Log data structure for event sourcing.
- **Data tiering**: Store data in memory and on SSD.
- **Global datastores**: Multi-region replication.
- **Serverless option**: No cluster management with automatic scaling.

### Memcached

- **Simple key-value store**: Optimized for simplicity.
- **Multi-threaded architecture**: Utilizes multiple cores effectively.
- **Auto-discovery**: Client library for node discovery.
- **Large item support**: Store larger objects.
- **SASL authentication**: Simple Authentication and Security Layer.
- **No persistence**: Purely in-memory caching.
- **Horizontal scaling**: Add and remove nodes as needed.

## Deployment Options

- **Redis OSS**:
    
    - **Cluster mode disabled**: Single-shard architecture.
    - **Cluster mode enabled**: Multi-shard architecture with horizontal scaling.
    - **Multi-AZ**: Automatic failover to replica in different AZ.
    - **Self-designed**: Manually configure replication.
- **Redis Serverless**:
    
    - **Fully managed**: No cluster management.
    - **Auto-scaling**: Automatically scales with workload.
    - **Pay-per-use**: Pay only for what you use.
- **Memcached**:
    
    - **Single-node**: Simple, single-instance deployment.
    - **Multi-node**: Horizontal scaling across multiple nodes.
    - **Auto-discovery**: Automatic node discovery for clients.

## Common Use Cases

- **Database query caching**: Cache frequent database queries.
- **Session stores**: Store session data for web applications.
- **Gaming leaderboards**: Using Redis sorted sets.
- **Content caching**: Cache frequently accessed content.
- **API response caching**: Cache REST API responses.
- **Real-time analytics**: Process data streams with Redis.
- **Message broker**: Pub/Sub functionality with Redis.
- **Geospatial applications**: Store and query geospatial data.
- **Machine learning feature stores**: Cache ML features.
- **Rate limiting**: Implement API rate limiting.
- **Job queues**: Implement simple job queues.
- **Chat applications**: Build real-time chat systems.
- **Page rendering acceleration**: Improve page load times.
- **Gaming data structures**: Store complex game state.
- **IoT data ingestion**: Buffer IoT data streams.

## Integration with AWS Services

- **[[Amazon RDS]]**: Cache database query results.
- **[[Amazon EC2]]**: Host applications that use ElastiCache.
- **[[AWS Lambda]]**: Serverless access to cache data.
- **[[Amazon Elastic Container Service (Amazon ECS)]]**: Container-based applications.
- - **[[Amazon Elastic Kubernetes Service (Amazon EKS)]]**: Container-based applications.
- **[[AWS Elastic Beanstalk]]]**: Web application caching.
- **[[Amazon API Gateway]]**: API response caching.
- **[[AWS Identity and Access Management (IAM)]]**: Authentication and authorization.
- **[[Amazon CloudWatch]]**: Monitoring and alerting.
- **[[AWS CloudTrail]]**: API audit logging.
- **[[AWS Backup]]**: Centralized backup management.
- **[[AWS CloudFormation]]**: Infrastructure as code deployment.
- **[[AWS PrivateLink]]**: Access ElastiCache without internet exposure.

## Benefits

- **Performance**: Microsecond latency for cached data.
- **Scalability**: Scale to terabytes of memory and millions of operations per second.
- **Availability**: Multi-AZ redundancy with automatic failover.
- **Cost-efficiency**: Reduce database load and associated costs.
- **Simplified management**: Fully managed service with minimal operational overhead.
- **Security**: Data encryption and VPC isolation.
- **Flexibility**: Choose the right engine for your use case.
- **Compatibility**: Industry-standard protocols and clients.
- **Monitoring**: Comprehensive metrics and logging.
- **Customization**: Tune parameters to match workload needs.
- **Global distribution**: Deploy globally with cross-region replication.

## Pricing

Amazon ElastiCache pricing is based on:

- **Node hours**: Hourly rate dependent on node type.
- **Reserved nodes**: Significant discounts for reserved capacity.
- **Data transfer**: Standard AWS data transfer rates apply.
- **Backup storage**: Charges for backup storage (Redis).
- **Serverless option**: Pay by the ElastiCache Serverless Compute Unit (ESCU) hour and GB-hour of data storage.

Pricing varies by region, instance type, and deployment option. Redis and Memcached have different pricing structures reflecting their capabilities.