---
group:
  - technology
---
AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage. It provides seamless integration between on-premises IT environments and AWS storage infrastructure.

## Key Features

- **Hybrid connectivity**: Connect on-premises environments to AWS storage.
- **Seamless integration**: Works with existing applications and workflows.
- **Optimized data transfer**: Local caching for low-latency access to frequently used data.
- **Bandwidth management**: Configure bandwidth usage for data transfer.
- **Encryption**: Data encrypted in transit and at rest.
- **Snapshot scheduling**: Automated, point-in-time snapshots of your data.
- **Monitoring and management**: [[Amazon CloudWatch]] integration for monitoring and alerting.
- **High availability**: Deploy in VMware HA environments for resilience.

## Gateway Types

### 1. S3 File Gateway

- Presents an NFS or SMB interface to local applications.
- Stores files as S3 objects with full S3 features.
- Local caching for low-latency access to recently used data.

**Common Use Cases**:

- File sharing and collaboration
- Backup and archive
- Data lakes and analytics
- Media workflows

### 2. FSx File Gateway

- Provides low-latency, on-premises access to fully managed, cloud-based file shares in [[Amazon FSx (for all types)]] for Windows File Server.
- Maintains local caching for frequently accessed data.

**Common Use Cases**:

- Windows application file storage
- User file shares
- Department shares

### 3. Volume Gateway

- Presents iSCSI block storage volumes to on-premises applications.
- Available in two modes:
    - **Cached volumes**: Primary data in [[Amazon S3]] with local cache for low-latency access.
    - **Stored volumes**: Primary data stored locally with asynchronous backups to S3.

**Common Use Cases**:

- Backup and disaster recovery
- Migration to cloud
- Tiered storage
- Main storage with cloud backup

### 4. Tape Gateway

- Presents an iSCSI virtual tape library (VTL) interface.
- Compatible with major backup software vendors.
- Virtual tapes stored in S3 and can be archived to [[Amazon S3 Glacier]].

**Common Use Cases**:

- Replacing physical tape libraries
- Long-term data retention
- Regulatory compliance

## Deployment Options

- **VMware ESXi**
- **Microsoft Hyper-V**
- **Linux KVM**
- **Hardware appliance**
- **[[Amazon EC2]]**

## Pricing

Pricing is based on:

- Gateway usage (per gateway per month)
- Storage pricing (based on the backing storage used - S3, EBS, etc.)
- Data transfer out from AWS
- Request pricing