---
group:
  - technology
---
Amazon S3 Glacier is a secure, durable, and extremely low-cost storage service for data archiving and long-term backup. It provides comprehensive security and compliance capabilities to meet demanding regulatory requirements.

## Key Features

- **Storage classes**: Three archive storage classes optimized for different archive use cases:
    - [[S3 Glacier Instant Retrieval]]: Millisecond retrieval for archive data that needs immediate access.
    - [[S3 Glacier Flexible Retrieval]]: Three retrieval options ranging from minutes to hours.
    - [[S3 Glacier Deep Archive]]: Lowest-cost storage for long-term archive with retrieval in hours.
- **Security and compliance**: Compliance with regulations like [[HIPAA]], [[PCI-DSS]], [[SEC]], and [[CJIS]].
- **Durability**: 99.999999999% (11 9's) durability for data protection.
- **Access control**: Integration with [[AWS Identity and Access Management (IAM)]] for resource-based permissions.
- **Encryption**: Data encrypted by default using AES-256.
- **Data immutability**: Vault Lock for write-once-read-many (WORM) compliance.
- **Audit capabilities**: Comprehensive audit trails with [[AWS CloudTrail]].

## Retrieval Options

For S3 Glacier Flexible Retrieval:

- **Expedited**: Urgent retrieval in 1-5 minutes.
- **Standard**: Retrieval in 3-5 hours.
- **Bulk**: Lowest-cost retrieval in 5-12 hours.

For S3 Glacier Deep Archive:

- **Standard**: Retrieval in 12 hours.
- **Bulk**: Lowest-cost retrieval in 48 hours.

## Common Use Cases

- **Long-term data archiving**: Cost-effective storage for data that needs to be retained for years.
- **Media archive storage**: Archive storage for media assets.
- **Scientific data preservation**: Store scientific, research, or genomic data.
- **Digital preservation**: Preservation of digital content.
- **Regulatory compliance**: Storage to meet regulatory data retention requirements.
- **Healthcare information archiving**: Long-term storage of healthcare information.
- **Financial data retention**: Archiving financial records.
- **Public sector data preservation**: Meeting government data retention mandates.

## Interfaces

- **S3 API**: Fully integrated with [[Amazon S3]] lifecycle policies.
- **Direct API**: S3 Glacier-specific API for advanced archive operations.
- **AWS Management Console**: Web-based interface for managing Glacier vaults and archives.
- **AWS SDKs**: Programmatic access through various language SDKs.

## Pricing

S3 Glacier pricing is based on:

- Storage volume
- Data retrieval (amount and speed)
- Data transfer out
- Request pricing

There are no minimum fees, and you only pay for what you use.