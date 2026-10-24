---
group:
  - technology
---
The AWS Snow Family is a collection of physical devices that help migrate large amounts of data into and out of AWS, or provide edge computing capabilities in environments with limited or no connectivity. These ruggedized, portable devices are designed to be secure and can operate in harsh environments where network connectivity is unreliable or unavailable.

## Snow Family Devices

### AWS Snowcone

The smallest member of the Snow Family:

- **Storage capacity**: 8 TB (HDD) or 14 TB (SSD)
- **Physical size**: Small, portable - 2.1 lbs (0.95 kg)
- **Network interfaces**: 10 Gb/1 Gb/100 Mb network interfaces
- **Computing options**: 2 vCPUs, 4 GB memory
- **Edge computing features**: EC2-compatible instances, AWS IoT Greengrass
- **Use cases**:
    - Edge computing
    - IoT data collection
    - Content distribution
    - Tactical edge computing
    - Small-scale data transfers

### AWS Snowball Edge

Mid-tier device available in compute optimized and storage optimized options:

#### Compute Optimized

- **Storage capacity**: 42 TB (NVMe SSD) or 80 TB (HDD)
- **Computing resources**: 104 vCPUs, 416 GB memory, optional GPU
- **Physical size**: Portable - 49.7 lbs (22.5 kg)
- **Network interfaces**: 25 Gb/10 Gb/1 Gb network interfaces

#### Storage Optimized

- **Storage capacity**: 80 TB (HDD)
- **Computing resources**: 40 vCPUs, 80 GB memory
- **Physical size**: Portable - 49.7 lbs (22.5 kg)
- **Network interfaces**: 25 Gb/10 Gb/1 Gb network interfaces

#### Use cases:

- Large data migrations
- Edge computing with higher compute requirements
- Machine learning at the edge
- Media processing
- Content distribution
- Temporary storage tier

### AWS Snowmobile

Exabyte-scale data transfer solution:

- **Storage capacity**: Up to 100 PB
- **Physical form**: 45-foot long ruggedized shipping container
- **Security features**: Physical security, dedicated security personnel
- **Use cases**:
    - Massive data center migrations
    - Media archives
    - Large-scale cloud migrations
    - Entire data center moves

## Key Features

- **High security**: Tamper-evident enclosures, 256-bit encryption, Trusted Platform Module (TPM).
- **Ruggedized design**: Weather-resistant, designed for harsh environments.
- **Offline data transfer**: Move data without relying on internet connectivity.
- **Edge computing**: Run EC2-compatible compute instances on the devices.
- **AWS service compatibility**: Support for S3, EBS, EC2, IoT Greengrass, and more.
- **Managed service**: End-to-end service managed by AWS.
- **Software compatibility**: NFS, SMB file interfaces for easy data access.
- **Online option**: Some devices can transfer data online via AWS DataSync.
- **Cluster capability**: Group multiple devices together for greater capacity and redundancy.
- **Scalability**: Scale from terabytes to exabytes with different devices.

## Common Use Cases

- **Large-scale data migration**: Move large datasets to AWS without network constraints.
- **Data center decommissioning**: Efficiently transfer data when closing data centers.
- **Content distribution**: Distribute content to remote locations.
- **Disaster recovery**: Back up critical data to or from AWS.
- **Remote site modernization**: Update data and applications at edge locations.
- **Media & entertainment workflows**: Process large media files at the edge.
- **IoT data collection**: Collect and process IoT data in remote locations.
- **Machine learning at the edge**: Run ML inference where connectivity is limited.
- **Tactical edge computing**: Support operations in remote or disconnected environments.
- **Cloud bursting**: Temporarily extend on-premises computing capacity.

## Data Transfer Process

1. **Order**: Request devices through the AWS Management Console.
2. **Receive**: AWS ships the device to your location.
3. **Connect**: Connect the device to your network.
4. **Transfer**: Copy data to or from the device.
5. **Return**: Ship the device back to AWS using the pre-paid shipping label.
6. **Process**: AWS transfers your data to or from your AWS storage services.
7. **Track**: Monitor progress through the AWS Management Console.

## Edge Computing Capabilities

- **EC2-compatible instances**: Run applications using Amazon EC2-compatible instances.
- **AWS IoT Greengrass**: Execute IoT applications locally.
- **Amazon EKS Anywhere**: Run Kubernetes clusters on Snow devices.
- **S3-compatible storage**: Access and store data using S3 API.
- **Block storage volumes**: Use EBS-compatible storage.
- **AMI support**: Use existing Amazon Machine Images.
- **Persistent compute**: Maintain operation for long-term deployments.
- **Lambda functions**: Run serverless functions at the edge.

## Security Features

- **256-bit encryption**: All data is automatically encrypted.
- **Tamper-evident seals**: Physical security measures to detect tampering.
- **TPM**: Trusted Platform Module for secure boot verification.
- **AWS KMS integration**: Key management using AWS KMS.
- **HIPAA compliance**: Support for HIPAA-regulated workloads.
- **Chain of custody**: Complete chain of custody tracking.
- **Secure erase**: Secure data wiping after import is complete.
- **IAM integration**: Role-based access control for device resources.

## Pricing

AWS Snow Family pricing varies by device and includes:

- **Service fee**: Per-device fee for device usage (daily or monthly rate)
- **Data transfer fee**: Charges for data transferred into AWS (first import job may be free)
- **Edge computing pricing**: Additional charges for compute features
- **Device usage**: Additional days beyond free period (varies by device)
- **Shipping**: Shipping costs vary by region and shipping speed

Specific pricing varies by region and device type. AWS offers pricing calculators to estimate total costs.