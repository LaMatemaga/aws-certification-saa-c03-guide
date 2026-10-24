---
group:
  - technology
---
AWS DataSync is a secure, online service that automates and accelerates moving data between on-premises storage systems and AWS storage services, as well as between AWS storage services. It can transfer file data, object data, and block volume data, simplifying data migration, data processing workflows, and archival for data storage.

## Key Features

- **Automated data transfer**: Automate data movement between on-premises and AWS storage.
- **High performance**: Transfer data at speeds up to 10 times faster than open-source tools.
- **End-to-end security**: Data encryption in transit and at rest with integrity validation.
- **Simple management**: Easily configure, monitor, and schedule data transfers.
- **Bandwidth throttling**: Control bandwidth usage to limit impact on networks.
- **Filtering**: Include or exclude specific files, folders, or objects based on patterns.
- **Metadata preservation**: Maintain file permissions, timestamps, and ownership.
- **Data verification**: Automatic data integrity verification during transfers.
- **Schedule transfers**: Set one-time or recurring transfer schedules.
- **Auto-discovery capabilities**: Discover object namespaces and file system hierarchies.
- **Delta transfers**: Only transfer new or modified files, reducing time and bandwidth.
- **Detailed metrics**: Comprehensive metrics and logs for monitoring transfers.
- **Multi-part parallel transfers**: Accelerate transfers of large files.

## Supported Storage Systems

### Source Locations

- **Network File System (NFS)**: NFS v3 and NFS v4.1 file servers
- **Server Message Block (SMB)**: SMB file servers
- **Hadoop Distributed File System (HDFS)**: Hadoop clusters
- **Self-managed object storage**: Compatible with S3 API
- **AWS storage services**: Amazon S3, Amazon EFS, Amazon FSx

### Destination Locations

- **Amazon S3**: All storage classes including Standard, Intelligent-Tiering, Standard-IA, One Zone-IA, Glacier, and Glacier Deep Archive
- **Amazon EFS**: Elastic File System
- **Amazon FSx**: FSx for Windows File Server, FSx for Lustre, FSx for OpenZFS, FSx for NetApp ONTAP
- **AWS Snow Family devices**: For offline data transfers

## Deployment Options

- **DataSync agent**: Virtual machine deployed in on-premises environments (VMware ESXi, KVM, Microsoft Hyper-V, or Amazon EC2)
- **Agentless transfers**: Direct transfers between AWS storage services
- **AWS Snowcone with DataSync**: Transfer data using Snowcone devices with integrated DataSync

## Common Use Cases

- **Data migration**: Move datasets to AWS quickly and securely.
- **Archival**: Transfer cold data to lower-cost storage classes in Amazon S3.
- **Data protection**: Copy data to AWS for backup and disaster recovery.
- **Data lake ingestion**: Transfer data into Amazon S3 for analytics and processing.
- **Storage tiering**: Move data between storage tiers based on access patterns.
- **Content distribution**: Replicate data across regions for improved performance.
- **Machine learning datasets**: Transfer large datasets for machine learning workloads.
- **Processing workflows**: Move data between storage services for processing pipelines.
- **Continuous replication**: Keep datasets synchronized between locations.

## Integration with AWS Services

- **Amazon CloudWatch**: Monitor transfer metrics and logs.
- **AWS CloudTrail**: Audit service API calls.
- **AWS Identity and Access Management**: Control access to DataSync resources.
- **AWS Key Management Service**: Manage encryption keys for secured transfers.
- **AWS PrivateLink**: Set up private connections between VPCs and DataSync.
- **Amazon EventBridge**: Automate workflows based on DataSync events.

## Benefits

- **Simplified data transfers**: Reduce development effort with automated transfers.
- **Accelerated migrations**: Move data quickly with high-performance transfers.
- **Enhanced security**: Secure transfers with encryption and integrity validation.
- **Reduced costs**: Save on development and infrastructure costs.
- **Operational efficiency**: Automate recurring data transfers.
- **Scalability**: Scale to handle transfers of any size.
- **Comprehensive logging**: Detailed visibility into transfer activities.
- **Flexibility**: Support for various storage types and transfer patterns.

## Pricing

AWS DataSync pricing is based on:

- Data transfer volume (per GB)
- No charges for data transfer INTO AWS (data ingress)
- Standard AWS charges apply for storage and data transfer OUT of AWS (data egress)
- No minimum fees or upfront commitments

Pricing varies by AWS region. You only pay for data transferred, with no charges for the DataSync service itself.