---
group:
  - technology
---
>[!Example] **Amazon Elastic Block Store (Amazon EBS):**
>Amazon Elastic Block Store (EBS) provides persistent block storage volumes for use with [[Amazon EC2]] instances. Each Amazon EBS volume is automatically replicated within its [[Availability Zone]] to protect against component failure.

## Key Features

- **Performance options**: Choose between SSD-backed storage optimized for transactional workloads (gp3, gp2, io2, io1) or HDD-backed storage optimized for throughput (st1, sc1).
- **Snapshots**: Create point-in-time snapshots of EBS volumes, which are stored in [[Amazon S3]] for long-term durability.
- **Encryption**: Encrypt EBS volumes with keys managed through [[AWS Key Management Service (KMS)]].
- **Elastic volumes**: Dynamically increase capacity, adjust performance, and change volume type with minimal disruption. 
- **Fast snapshot restore**: Initialize volumes from snapshots quickly with fast snapshot restore.
- **Multi-attach**: Attach a single io2 volume to multiple instances for clustered applications.
- **Data lifecycle manager**: Automate snapshot creation, retention, and deletion.

## Common Use Cases

- **Boot volumes**: Operating system volumes for EC2 instances.
- **Database storage**: Reliable storage for database workloads.
- **Enterprise applications**: Storage for enterprise applications requiring consistent performance.
- **Big data analytics**: Storage for data analytics applications.
- **Development and test environments**: Quickly create and destroy storage for development.

## Volume Types

1. **General Purpose SSD (gp3/gp2)**: Balance of price and performance for a wide variety of workloads.
2. **Provisioned IOPS SSD (io2/io1)**: High-performance SSD for mission-critical workloads.
3. **Throughput Optimized HDD (st1)**: Low-cost HDD for frequently accessed, throughput-intensive workloads.
4. **Cold HDD (sc1)**: Lowest cost HDD for less frequently accessed workloads.

## Pricing

Pricing is based on the volume type, size, and for some volume types, the performance you provision. You are billed for the provisioned amount of storage, not the amount used.