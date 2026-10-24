---
group:
  - technology
---
Amazon S3 is an object storage service that offers industry-leading scalability, data availability, security, and performance. It can store and retrieve any amount of data from anywhere on the web and is designed to deliver 99.999999999% (11 9's) of durability.

## Key Features

- **Durability and availability**: S3 is designed for 99.999999999% durability and 99.99% availability.
- **Storage classes**: Multiple storage classes optimized for different use cases:
    - [[S3 Standard]]: General-purpose storage for frequently accessed data.
    - [[S3 Intelligent-Tiering]]: Automatic cost savings for data with unknown or changing access patterns.
    - [[S3 Standard-IA]]: For infrequently accessed data that requires millisecond retrieval.
    - [[S3 One Zone-IA]]: For infrequently accessed data that doesn't require multi-AZ resilience.
    - [[S3 Glacier Instant Retrieval]]: For archive data that requires millisecond retrieval.
    - [[S3 Glacier Flexible Retrieval]]: For archive data with retrieval times from minutes to hours.
    - [[S3 Glacier Deep Archive]]: Lowest-cost storage for long-term archive with retrieval times of hours.
- **Bucket and object operations**: Create buckets, store unlimited objects, download, copy, and move data.
- **Security and access control**: [[AWS Identity and Access Management (IAM)]] policies, bucket policies, ACLs, and S3 Block Public Access.
- **Data processing**: Transform data and trigger workflows with S3 event notifications.
- **Strong consistency**: Read-after-write consistency for PUT and DELETE operations.
- **Storage management**: Lifecycle policies, versioning, replication, batch operations.
- **Access management and security**: Various options for controlling access to data.
- **Data processing and analysis**: [[AWS Lambda]], S3 Select, [[Amazon Athena]], and Redshift Spectrum integration.
- **Monitoring and analytics**: [[Amazon CloudWatch]] metrics, event notifications, and storage analytics.

## Common Use Cases

- **Backup and storage**: Reliable, scalable, and secure storage for backups and archives.
- **Disaster recovery**: Cross-region replication for disaster recovery solutions.
- **Data lakes**: Foundation for data lakes that combine with AWS analytics services.
- **Content distribution**: Store and distribute content, images, and media.
- **Static website hosting**: Host static websites with high availability.
- **Big data analytics**: Data storage for big data analytics applications.
- **Mobile applications**: Storage for mobile application data.
- **IoT device data**: Storage for Internet of Things sensor data.

## Pricing

Amazon S3 pricing is based on:

- Storage class and volume
- Data transfer (out of AWS)
- Request and data retrieval
- Management and analytics features
- Data transfer acceleration
- Cross-region replication

There are no minimum fees, and you only pay for what you use.