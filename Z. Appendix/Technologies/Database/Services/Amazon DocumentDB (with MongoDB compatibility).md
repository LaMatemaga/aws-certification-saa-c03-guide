---
group:
  - technology
---
Amazon DocumentDB is a fast, scalable, highly available, and fully managed document database service that supports MongoDB workloads. It is designed from the ground up to be compatible with MongoDB, allowing you to use the same application code, drivers, and tools as you do with MongoDB while benefiting from the scalability, availability, and security of an AWS managed service.

## Key Features

- **MongoDB compatibility**: Compatible with MongoDB 3.6, 4.0, 5.0, and 6.0 APIs.
- **Fully managed service**: AWS handles administration, patching, and backups.
- **Distributed, fault-tolerant architecture**: Six copies of data across three AWS Availability Zones.
- **Storage auto-scaling**: Automatically grows storage as needed.
- **High availability**: 99.99% availability with automated failover in seconds.
- **Performance at scale**: Millions of requests per second with millisecond latency.
- **Automated backups**: Continuous backup with point-in-time recovery.
- **Security**: Data encryption at rest and in transit.
- **Instance scaling**: Scale compute capacity up or down in minutes.
- **Read scaling**: Up to 15 read replicas for read-heavy workloads.
- **Global clusters**: Distribute data globally with cross-region replicas.
- **Change streams**: Capture and react to data changes.
- **Elastic clusters**: Distributed clusters that scale to petabytes (Preview).
- **Full-text search**: Integrated search functionality.
- **Time series collections**: Store and query time series data efficiently.

## Instance Types and Configurations

- **Instance classes**: Various instance types optimized for different workloads:
    - **Memory optimized (r-classes)**: For memory-intensive applications.
    - **Burstable (t-classes)**: For development and test environments.
- **Deployment options**:
    - **Standard clusters**: Traditional single-primary cluster.
    - **Elastic clusters**: Distributed architecture for horizontal scaling (Preview).
    - **Global clusters**: Clusters spanning multiple AWS regions.

## Storage Architecture

- **Separated storage and compute**: Scale each independently.
- **Distributed storage system**: Six copies of data across three AZs.
- **Automatic storage scaling**: Starts at 10 GB and scales up to 128 TB.
- **Purpose-built database engine**: Optimized for document workloads.
- **Durability focus**: 99.999999999% (11 nines) durability design.

## MongoDB Compatibility Features

- **BSON document model**: Support for nested documents and arrays.
- **MongoDB query language**: Query capabilities from MongoDB.
- **MongoDB drivers**: Compatible with standard MongoDB drivers.
- **MongoDB tools**: Works with mongodump, mongorestore, etc.
- **MongoDB APIs**: Support for CRUD operations, aggregation pipeline, etc.
- **Indexes**: Support for various index types (single-field, compound, multi-key, TTL).
- **Data types**: Support for all MongoDB data types.
- **Authentication**: SCRAM-SHA-1 and SCRAM-SHA-256 authentication.
- **Role-based access control**: MongoDB roles and privileges.

## Common Use Cases

- **Content management systems**: Store and manage content with flexible schemas.
- **User profiles and preferences**: Manage user data with varying attributes.
- **Mobile applications**: Backend for mobile apps needing flexible data storage.
- **Real-time big data applications**: Process and store large volumes of data.
- **Catalog and inventory management**: Store product data with varying attributes.
- **Gaming applications**: Store game state and player data.
- **IoT applications**: Ingest and query data from IoT devices.
- **MongoDB migrations**: Move from self-managed MongoDB to managed service.
- **Microservices data stores**: Persistent storage for microservices.
- **Operational analytics**: Real-time analysis of operational data.
- **Event logging**: Capture and query application events.
- **Personalization systems**: Store customer preferences and behaviors.

## Integration with AWS Services

- **[[AWS Identity and Access Management (IAM)]]**: Authentication and authorization.
- **[[Amazon VPC]]**: Network isolation and security.
- **[[AWS Database Migration Service (AWS DMS)]]**: Migrate data to DocumentDB.
- **[[AWS Secrets Manager]]**: Store and rotate database credentials.
- **[[Amazon CloudWatch]]**: Monitoring and alerting.
- **[[AWS Lambda]]**: Process change streams and database events.
- **[[AWS Glue]]**: ETL for data integration.
- **[[Amazon QuickSight]]**: Visualization and business intelligence.
- **[[AWS CloudFormation]]**: Infrastructure as code deployment.
- **[[AWS Backup]]**: Centralized backup management.

## Benefits

- **Operational simplicity**: Fully managed with no administration overhead.
- **Scalability**: Scale storage and compute independently.
- **Availability**: Built for 99.99% availability.
- **Durability**: 99.999999999% (11 nines) durability.
- **Performance**: High throughput and low latency.
- **Security**: Comprehensive security capabilities.
- **Cost-effective**: Pay only for resources used.
- **MongoDB compatibility**: Use existing MongoDB expertise and tools.
- **Integration**: Works with AWS ecosystem.
- **Global distribution**: Support for multi-region deployments.

## Pricing

Amazon DocumentDB pricing is based on:

- **Instance hours**: Hourly rate dependent on instance class.
- **Storage usage**: Pay per GB-month of storage used.
- **I/O operations**: Pay per million I/O requests.
- **Backup storage**: Free backup storage up to 100% of database storage.
- **Data transfer**: Standard AWS data transfer rates apply.
- **Elastic clusters**: Pay for vCPU hours, storage, and IOPS.

Pricing varies by region, and reserved instances are available for cost savings on long-term commitments.