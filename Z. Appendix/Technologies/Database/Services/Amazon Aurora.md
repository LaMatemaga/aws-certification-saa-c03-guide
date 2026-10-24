---
group:
  - technology
---
Amazon Aurora is a MySQL and PostgreSQL-compatible relational database built for the cloud that combines the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open source databases. It is designed to deliver up to five times the throughput of standard MySQL and up to three times the throughput of standard PostgreSQL.

## Key Features

- **High performance**: Significantly faster than standard MySQL and PostgreSQL.
- **High availability**: Automated multi-AZ replication with 99.99% availability.
- **Self-healing storage**: Automatically recovers from physical storage failures.
- **Distributed architecture**: Storage is distributed across multiple nodes.
- **Automatic scaling**: Storage automatically grows up to 128 TiB per database instance.
- **Backup and recovery**: Automated continuous backups with point-in-time recovery.
- **Read scaling**: Up to 15 read replicas with minimal replica lag.
- **Global database**: Replicate across AWS regions with low latency global reads.
- **Database cloning**: Create new databases that share the same data quickly.
- **Serverless option**: Auto-scaling with Aurora Serverless.
- **MySQL and PostgreSQL compatibility**: Use existing tools and skills.
- **Multi-master capability**: Scale write operations across multiple instances.
- **Parallel query**: Accelerate analytical queries on Aurora MySQL.
- **Backtrack**: Roll back database to a previous state without restoring from backup.
- **Zero-downtime patching**: Apply security patches without downtime.
- **Zero-ETL integration**: Replicate data directly to Amazon Redshift in near real-time.

## Database Engines

- **Aurora MySQL**: Compatible with MySQL 5.7 and 8.0.
- **Aurora PostgreSQL**: Compatible with PostgreSQL 11, 12, 13, 14, and 15.

## Instance Types and Configurations

- **Instance classes**: Various instance types optimized for different workloads:
    - **Memory optimized (r-classes)**: For memory-intensive applications.
    - **Burstable (t-classes)**: For development and test environments.
    - **I/O optimized (i-classes)**: For I/O-intensive workloads.
- **Deployment options**:
    - **Provisioned**: Traditional instances with fixed capacity.
    - **Serverless**: Auto-scaling based on workload needs.
    - **Multi-master**: Multiple writable instances for high availability.
    - **Global database**: Clusters spanning multiple regions.

## Storage Architecture

- **Distributed, fault-tolerant storage**: Data replicated across 6 copies in 3 AZs.
- **Self-healing**: Continuously scans for errors and repairs automatically.
- **Storage auto-scaling**: Automatically grows from 10 GiB to 128 TiB.
- **Page server caching**: Reduces I/O and improves performance.
- **Log-structured storage**: Optimized for database workloads.
- **Continuous backup**: Data continuously backed up to Amazon S3.

## Common Use Cases

- **Enterprise applications**: High performance for critical business applications.
- **SaaS applications**: Multi-tenant applications requiring scalability.
- **Gaming applications**: Applications with high throughput and low latency needs.
- **Web and mobile applications**: Consumer-facing applications with variable loads.
- **E-commerce platforms**: Business-critical applications requiring high availability.
- **Financial systems**: Applications requiring data accuracy and consistency.
- **Hybrid migrations**: Transitioning on-premises databases to cloud.
- **High availability requirements**: Applications that cannot afford downtime.
- **Development and test environments**: With Aurora Serverless for cost optimization.
- **Read-heavy workloads**: Using multiple read replicas for scalability.
- **Global applications**: Using Global Database for worldwide availability.
- **Analytical queries**: Using Parallel Query to accelerate analysis.

## Integration with AWS Services

- **[[AWS Identity and Access Management (IAM)]]**: Authentication and authorization.
- **[[Amazon S3]]**: Export snapshots and import data.
- **[[AWS Database Migration Service (AWS DMS)]]**: Migrate to Aurora from other databases.
- **[[AWS Secrets Manager]]**: Manage database credentials.
- **[[Amazon RDS Proxy]]**: Connection pooling for improved scalability.
- **[[AWS Lambda]]**: Serverless event triggers and integration.
- **[[Amazon CloudWatch]]**: Monitoring and logging.
- **[[AWS Backup]]**: Centralized backup management.
- **[[AWS CloudFormation]]**: Infrastructure as code provisioning.
- **[[Amazon Redshift]]**: Data integration for analytics (Zero-ETL).
- **[[AWS Glue]]**: Data integration and ETL.

## Benefits

- **Performance**: Up to 5x throughput of MySQL, 3x of PostgreSQL.
- **Availability**: 99.99% availability with automated failover.
- **Scalability**: Automatic storage scaling and read scalability.
- **Cost-effective**: Pay only for what you use.
- **Compatibility**: Use existing MySQL and PostgreSQL tools.
- **Managed service**: AWS handles administrative tasks.
- **Durability**: 99.999999999% (11 nines) durability.
- **Security**: Advanced security features and encryption.
- **Innovation**: Continuous new features and improvements.
- **Global reach**: Deploy across multiple regions.

## Pricing

Amazon Aurora pricing is based on:

- **Instance hours**: Hourly rate dependent on instance class.
- **Storage usage**: Pay per GB-month of storage used.
- **I/O operations**: Pay per million I/O requests.
- **Backup storage**: Free backup storage up to 100% of database storage.
- **Data transfer**: Standard AWS data transfer rates apply.

Aurora offers a free tier for new AWS customers and reserved instances for cost savings on long-term commitments.