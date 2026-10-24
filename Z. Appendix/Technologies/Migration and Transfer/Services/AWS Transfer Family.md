---
group:
  - technology
---
AWS Transfer Family is a secure transfer service that enables you to transfer files into and out of Amazon S3 storage and Amazon EFS file systems using the Secure File Transfer Protocol (SFTP), File Transfer Protocol over SSL (FTPS), and File Transfer Protocol (FTP). This fully managed service helps you migrate your file transfer workflows to AWS while maintaining your existing client applications and users.

## Key Features

- **Multiple protocol support**: SFTP (SSH File Transfer Protocol), FTPS (FTP Secure), and FTP.
- **Fully managed service**: No servers to manage or maintain.
- **Amazon S3 and EFS integration**: Store transferred files in Amazon S3 buckets or EFS file systems.
- **Identity provider options**: Multiple authentication methods including service-managed, AWS Directory Service, custom identity providers.
- **Custom domains**: Use your own domain names for file transfer endpoints.
- **Client authentication**: Password or key-based authentication.
- **AWS service integrations**: Integrate with services like Lambda, CloudWatch, and CloudTrail.
- **VPC support**: Create endpoints within your VPC for enhanced security.
- **Scaling capabilities**: Automatically scales to meet your transfer demands.
- **AS2 protocol support**: Exchange EDI documents securely using AS2 protocol.
- **Workflows**: Automate file processing after upload.
- **File event notifications**: Get notified when files are uploaded or downloaded.
- **Logical directories**: Create virtual directory structures that map to different S3 prefixes or EFS paths.
- **Security features**: TLS encryption, VPC security groups, IAM policies.

## Transfer Protocols

- **SFTP (Secure Shell File Transfer Protocol)**: Secure file transfers over SSH.
- **FTPS (File Transfer Protocol Secure)**: FTP with TLS encryption.
- **FTP (File Transfer Protocol)**: Standard unencrypted file transfer protocol.
- **AS2 (Applicability Statement 2)**: Secure and reliable transport for B2B transactions.

## Identity Management Options

- **Service-managed users**: Users and keys managed within the service.
- **AWS Directory Service for Microsoft Active Directory**: Integrate with your existing AD users.
- **Custom identity providers**: Connect to your existing identity management systems.
- **AWS Lambda integration**: Custom authentication and authorization.
- **AWS IAM**: Role-based access control for transfers.

## Storage Options

- **Amazon S3**: Store files in Amazon S3 buckets with various storage classes.
- **Amazon EFS**: Store files in Elastic File System for file system semantics.
- **Logical directories**: Map virtual directories to different S3 prefixes or EFS paths.
- **Home directories**: Automatically route users to their home directory.

## Common Use Cases

- **B2B file transfers**: Exchange files with partners and customers.
- **Legacy system migrations**: Move legacy file transfer systems to AWS.
- **Compliance requirements**: Meet regulatory requirements for secure file transfers.
- **Electronic Data Interchange (EDI)**: Transfer EDI documents securely using AS2.
- **Supply chain integration**: Connect with suppliers and vendors.
- **Content uploads and downloads**: Enable secure content distribution.
- **Large file transfers**: Handle large file transfers that are impractical over HTTP.
- **Financial data exchange**: Securely exchange financial information.
- **Healthcare data transfers**: HIPAA-compliant file transfers.
- **Backup and archive**: Transfer files to AWS for backup and archival purposes.

## AWS Transfer Family Workflows

- **Post-upload processing**: Automatically process files after upload.
- **Custom steps**: Define custom processing steps with Lambda.
- **File validation**: Validate uploaded files for content and structure.
- **File decryption/encryption**: Decrypt or encrypt files during processing.
- **File format conversion**: Convert between different file formats.
- **Tag-based routing**: Route files based on metadata tags.
- **Notifications**: Generate notifications upon workflow completion.
- **Error handling**: Configure custom error handling procedures.
- **Audit and logging**: Track all file processing operations.

## Security Features

- **Data encryption**: Data encrypted in transit and at rest.
- **Network security**: VPC endpoints and security groups.
- **Access control**: Fine-grained access control with IAM policies.
- **Authentication**: Multiple authentication mechanisms including SSH keys and passwords.
- **Audit logging**: Integration with AWS CloudTrail.
- **Compliance**: Supports compliance with HIPAA, PCI DSS, and other standards.
- **Private endpoints**: Create endpoints accessible only within your VPC.
- **Managed IP allow lists**: Control which IP addresses can connect to your endpoints.
- **Certificate management**: Manage TLS certificates for FTPS connections.

## Integration with AWS Services

- **Amazon S3**: Store files in S3 buckets.
- **Amazon EFS**: Store files in Elastic File System.
- **AWS Lambda**: Custom authentication and file processing.
- **Amazon CloudWatch**: Monitor transfer activities.
- **AWS CloudTrail**: Audit API calls and user activities.
- **AWS Identity and Access Management**: Control access to resources.
- **Amazon EventBridge**: React to file transfer events.
- **AWS Secrets Manager**: Store and retrieve credentials.
- **Amazon SNS**: Send notifications about transfers.
- **AWS Certificate Manager**: Manage certificates for FTPS.

## Benefits

- **Simplified migration**: Easily migrate existing file transfer workflows to AWS.
- **No infrastructure management**: Fully managed service with no servers to maintain.
- **Cost-effective**: Pay only for what you use without upfront costs.
- **Scalability**: Automatically scales to handle varying transfer loads.
- **Security**: Enterprise-grade security features.
- **Compatibility**: Works with existing clients and applications.
- **High availability**: Built on AWS's reliable infrastructure.
- **Global reach**: Access file transfer endpoints globally.
- **Simplified operations**: Centralized management and monitoring.
- **Automation**: Automated workflows for file processing.

## Pricing

AWS Transfer Family pricing is based on:

- **Endpoint hours**: Hourly rate for each protocol endpoint.
- **Data transfer**: Charges for data uploaded or downloaded.
- **Storage**: Standard S3 or EFS storage rates apply.
- **Additional features**: Charges for features like workflows.

Pricing varies by AWS region. There are no upfront commitments, and you pay only for what you use.