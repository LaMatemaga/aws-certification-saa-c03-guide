---
group:
  - technology
---
Amazon Relational Database Service (RDS) is a managed relational database service that makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching, and backups.

## Key Features

- **Managed service**: AWS handles routine database tasks.
- **Multiple database engines**: Support for MySQL, PostgreSQL, MariaDB, Oracle, Microsoft SQL Server, and IBM Db2.
- **Easy scaling**: Vertical scaling of compute and storage.
- **Automated backups**: Point-in-time recovery with automated backups.
- **Manual snapshots**: User-initiated database snapshots.
- **Multi-AZ deployments**: High availability with synchronous replication.
- **Read replicas**: Horizontal read scaling with asynchronous replication.
- **Security**: Network isolation, encryption, and access control.
- **Monitoring**: Integrated monitoring and metrics.
- **Maintenance windows**: Control when updates and patches are applied.
- **Parameter groups**: Customize database engine configuration.
- **Event notification**: Monitor and respond to database events.
- **Performance Insights**: Database performance monitoring and tuning.
- **Automated software patching**: Stay current with latest patches.
- **Storage autoscaling**: Automatically increase storage as needed.
- **Resource-level permissions**: Fine-grained access control.
- **Cross-region replication**: Replicate databases across AWS regions.
- **Blue/Green deployments**: Create staging environments for database changes.

## Database Engines

- **MySQL**: Versions 5.7, 8.0
- **PostgreSQL**: Versions 10, 11, 12, 13, 14, 15
- **MariaDB**: Versions 10.3, 10.4, 10.5, 10.6
- **Oracle**: Versions 12c, 19c, 21c
- **Microsoft SQL Server**: Versions 2016, 2017, 2019, 2022
- **IBM Db2**: Various versions

## Deployment Options

- **Standard deployments**: Traditional database instances.
- **Multi-AZ deployments**: Synchronous standby replica in a different availability zone.
- **Read replicas**: Read-only copies for scaling read operations.
- **Global databases**: Cross-region replicas for global applications.
- **On-demand instances**: Pay for compute capacity by the hour.
- **Reserved instances**: Discounted pricing with term commitments.
- **Serverless**: Auto-scaling configuration with Aurora Serverless.

## Instance Types

- **Standard**: General-purpose instances balanced for compute and memory.
- **Memory Optimized**: High memory-to-vCPU ratio for memory-intensive workloads.
- **Burstable**: Cost-effective instances for lower average CPU utilization.
- **Custom instance types**: Engine-specific options for Oracle and SQL Server.

## Storage Options

- **General Purpose (SSD)**: Balanced performance and cost for most workloads.
- **Provisioned IOPS (SSD)**: High-performance storage for I/O-intensive workloads.
- **Magnetic**: Legacy storage option for backward compatibility.
- **Storage autoscaling**: Automatically increase storage when needed.
- **Storage scaling**: Modify storage capacity without downtime.

## High Availability and Disaster Recovery

- **Multi-AZ deployments**: Synchronous replication to standby replica.
- **Automated failover**: Automatic failover to standby in case of issues.
- **Cross-region replication**: Replicate databases to different regions.
- **Automated backups**: Daily full backups and transaction logs.
- **Database snapshots**: Manual backups initiated by users.
- **Point-in-time recovery**: Restore to any point within the retention period.
- **Fast recovery**: Quick recovery from backups or snapshots.
- **Pilot Light setups**: Maintain minimal standby environment.

## Performance Features

- **Performance Insights**: Database performance monitoring and analysis.
- **Enhanced Monitoring**: Detailed OS metrics for database instances.
- **Slow query logs**: Identify and analyze slow SQL queries.
- **Query execution plans**: Analyze how databases execute queries.
- **Resource metrics**: Track CPU, memory, storage, and I/O metrics.
- **Performance recommendations**: Automated database performance recommendations.
- **Parameter tuning**: Optimize database engine parameters.

## Security Features

- **Network isolation**: Run databases in Amazon VPC.
- **Security groups**: Control network access to databases.
- **IAM authentication**: Database authentication using IAM.
- **Encryption at rest**: Encrypt database and backups.
- **Encryption in transit**: Secure data in transit with SSL/TLS.
- **Key management**: Integration with AWS KMS for key management.
- **Audit logging**: Track database activities with audit logs.
- **Compliance certifications**: Meet various compliance requirements.

## Common Use Cases

- **Web applications**: Backend database for websites and applications.
- **E-commerce platforms**: Store product catalogs and order information.
- **Content management systems**: Database backend for CMS platforms.
- **Customer relationship management**: Store customer data and interactions.
- **Mobile applications**: Backend database for mobile apps.
- **Enterprise applications**: Database tier for enterprise workloads.
- **SaaS applications**: Multi-tenant database architecture.
- **Development and testing**: Database environments for development.
- **Legacy application migration**: Move on-premises databases to cloud.
- **Data warehousing**: Store structured data for analytics.
- **Gaming applications**: Store game state and player information.
- **Analytics**: Store and retrieve analytical data.
- **Healthcare applications**: Store patient records and medical data.
- **Financial applications**: Store transactional financial data.

## Integration with AWS Services

- **[[AWS Identity and Access Management (IAM)]]**: Authentication and authorization.
- **[[Amazon VPC]]**: Network isolation and security.
- **[[AWS Database Migration Service (DMS)]]**: Database migration.
- **[[AWS Schema Conversion Tool (SCT)]]**: Convert database schemas.
- **[[Amazon S3]]**: Export and import data, store backups.
- **[[AWS Lambda]]**: Serverless database triggers and processing.
- **[[Amazon CloudWatch]]**: Monitoring and alerting.
- **[[AWS Secrets Manager]]**: Manage database credentials.
- **[[AWS Backup]]**: Centralized backup management.
- **[[AWS CloudFormation]]**: Infrastructure as code deployment.
- **[[Amazon EventBridge]]**: Respond to database events.
- **[[AWS PrivateLink]]**: Private connectivity to databases.

## Benefits

- **Easy administration**: Simplified database management.
- **High availability**: Multi-AZ deployments with automatic failover.
- **Scalability**: Easily scale compute and storage resources.
- **Security**: Comprehensive security features.
- **Performance**: Optimized for database workloads.
- **Cost-effective**: Pay only for resources used.
- **Compatibility**: Support for standard database engines.
- **Managed updates**: Automated patching and minor version upgrades.
- **Monitoring**: Built-in monitoring and performance tools.
- **Backup and recovery**: Automated backup and point-in-time recovery.

## Pricing

Amazon RDS pricing is based on:

- **Instance hours**: Hourly rate dependent on instance class.
- **Storage**: Pay per GB-month of provisioned storage.
- **I/O operations**: Pay per million I/O requests (for Magnetic storage).
- **Provisioned IOPS**: Pay for provisioned IOPS (if using Provisioned IOPS storage).
- **Backup storage**: Free backup storage up to 100% of database storage.
- **Data transfer**: Standard AWS data transfer rates apply.

Reserved instances offer significant discounts with 1-year or 3-year term commitments. Pricing varies by region, database engine, and instance type.