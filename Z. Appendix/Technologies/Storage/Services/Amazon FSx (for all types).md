---
group:
  - technology
---
>[!Example] **Amazon FSx:**
>Amazon FSx provides fully managed, feature-rich file systems that are built on common open source and commercially-licensed file systems. FSx makes it easy to launch, run, and scale shared file storage in the AWS Cloud.

## FSx for Windows File Server

A fully managed native Microsoft Windows file system that provides shared file storage for Windows-based applications.

### Key Features

- **Windows compatibility**: Native support for Windows file system features and SMB protocol.
- **Active Directory integration**: Seamlessly join your Microsoft Active Directory domain.
- **Data deduplication**: Reduce storage costs by eliminating redundant data.
- **Storage options**: Choose SSD or HDD storage options.
- **Performance optimization**: Scale up to hundreds of thousands of IOPS with sub-millisecond latencies.
- **High availability**: Multi-AZ deployment options for high availability.

### Common Use Cases

- **Windows application storage**: File storage for Windows applications.
- **User shares**: Home directories and departmental shares.
- **Content management**: Storing and serving web content.
- **Data analytics**: Storage for Windows-based analytics applications.

## FSx for Lustre

A fully managed file system that is optimized for compute-intensive workloads, such as high-performance computing, machine learning, media data processing workflows, and electronic design automation.

### Key Features

- **High performance**: Hundreds of GB/s of throughput and millions of IOPS.
- **S3 integration**: Seamlessly link to [[Amazon S3]] buckets.
- **Deployment types**: Choose between scratch (temporary) and persistent storage.
- **Data compression**: Compress data to reduce storage costs.

### Common Use Cases

- **High-performance computing**: Storage for HPC workloads.
- **Machine learning**: Training and inference for ML models.
- **Media processing**: Storage for media processing workflows.
- **Financial analytics**: Storage for financial modeling and analysis.

## FSx for NetApp ONTAP

A fully managed file system that's built on NetApp's ONTAP file system, providing multi-protocol access to data with features like snapshots, replication, and compression.

### Key Features

- **Multi-protocol access**: Support for NFS, SMB, and iSCSI protocols.
- **Storage efficiency**: Compression, deduplication, and thin provisioning.
- **Data protection**: Snapshots, replication, and backups.
- **Performance tiers**: Automatic tiering between SSD and capacity pool storage.

### Common Use Cases

- **Lift and shift**: Move on-premises ONTAP workloads to AWS.
- **Enterprise applications**: Storage for mission-critical applications.
- **DevOps**: Multi-protocol access for development and operations.

## FSx for OpenZFS

A fully managed file system that's built on the OpenZFS file system, providing high-performance file storage with features like snapshots and compression.

### Key Features

- **NFS protocol support**: Native support for the NFS protocol (v3, v4, v4.1, v4.2).
- **High performance**: Hundreds of thousands of IOPS with sub-millisecond latencies.
- **Data protection**: Snapshots and data compression.
- **Cloning**: Instant creation of new file systems from snapshots.

### Common Use Cases

- **Home directories**: User home directory storage.
- **Development environments**: Storage for development and testing.
- **Content management**: Storage for web and content servers.
- **Analytics**: Storage for data analytics applications.

## Pricing

Pricing varies by FSx type but generally includes charges for storage capacity, throughput capacity, and backup storage used.