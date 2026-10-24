---
group:
  - technology
---
>[!Example] **Amazon Elastic File System (Amazon EFS):**
>Amazon Elastic File System (EFS) provides scalable, elastic, cloud-native NFS file storage for use with AWS Cloud services and on-premises resources. It is built to scale on demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files.

## Key Features

- **Elastic capacity**: Automatically grows and shrinks as you add and remove files.
- **Performance modes**: Choose between General Purpose mode for latency-sensitive use cases or Max I/O mode for higher aggregate throughput.
- **Throughput modes**: Select Bursting Throughput based on storage size or Provisioned Throughput independent of storage size.
- **Storage classes**: Choose between EFS Standard for frequently accessed files and EFS Infrequent Access (IA) for files accessed less frequently.
- **Lifecycle management**: Automatically move files between storage classes based on access patterns.
- **Security**: Control network access with security groups and IAM policies.
- **Encryption**: Data encrypted at rest and in transit.
- **Shared access**: Thousands of [[Amazon EC2]] instances can access an EFS file system concurrently.
- **Regional access**: Mount from all [[Availability Zone]]s in a [[region]].

## Common Use Cases

- **Content management systems**: Store and serve web content.
- **Development environments**: Share code and other files across development teams.
- **Container storage**: Persistent shared storage for Kubernetes or [[Amazon Elastic Container Service (Amazon ECS)]].
- **Big data analytics**: Storage for analytics applications.
- **Media processing workflows**: Storage for media processing applications.
- **Web serving and content management**: Serve and manage website content.

## Access Methods

- **Mount targets**: Create mount targets in each Availability Zone to access your file system.
- **AWS Direct Connect or VPN**: Access from on-premises servers.
- **EFS mount helper**: Simplifies mounting EFS file systems.
- **Access points**: Create application-specific entry points into an EFS file system.

## Pricing

Pricing is based on the amount of data stored in your file system and the storage class used (Standard or Infrequent Access). There are no minimum fees or setup costs.