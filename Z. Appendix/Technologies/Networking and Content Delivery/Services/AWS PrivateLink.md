---
group:
  - technology
---
AWS PrivateLink is a highly available, scalable technology that enables you to privately connect your VPC to services as if they were in your VPC, without using public IPs, and without requiring traffic to traverse the internet. This service simplifies the security of data shared with cloud-based applications by eliminating the exposure of data to the public internet.

## Key Features

- **Private connectivity**: Connect to services outside your VPC without using public IPs or requiring internet gateway.
- **Service endpoints**: Access AWS services privately via service endpoints in your VPC.
- **Endpoint services**: Make your applications available to other AWS customers without internet exposure.
- **Interface VPC endpoints**: Connect to supported AWS services, services hosted by other AWS accounts, and supported AWS Marketplace partner services.
- **Gateway Load Balancer endpoints**: Access third-party virtual appliances.
- **Security groups**: Control traffic to your interface endpoints using security groups.
- **Private DNS**: Use custom private DNS names for your endpoint services.
- **Multiple VPC support**: Connect multiple VPCs to the same service.
- **Access control**: Grant permissions to specific AWS principals to use your endpoint service.
- **Network load balancer integration**: Use network load balancers as the entry point for your services.
- **Inter-region access**: Access services across different AWS regions.

## Components

- **VPC endpoints**: Allow you to privately connect your VPC to supported services.
    - **Interface endpoints**: Elastic network interfaces with private IPs that serve as entry points for traffic.
    - **Gateway Load Balancer endpoints**: Connect to services that run behind a Gateway Load Balancer.
    - **Gateway endpoints**: A gateway that you specify as a target for a route to a supported service (S3 and DynamoDB only).
- **Endpoint services (AWS PrivateLink)**: Allow you to expose your service to other VPCs.
    - **Network Load Balancer**: Distributes traffic to your service.
    - **Permissions**: Control which AWS principals can connect to your service.
    - **Private DNS**: Custom DNS names for your service.

## Supported Services

- **AWS services**: Most AWS services support interface endpoints (e.g., S3, DynamoDB, SQS, SNS, etc.).
- **Your own services**: Services you host on EC2 instances, containers, or serverless functions.
- **Third-party services**: Services available through AWS Marketplace.
- **Services from other AWS accounts**: Access services owned by other AWS accounts.

## Common Use Cases

- **Secure access to AWS services**: Access AWS services without internet exposure.
- **Shared services architecture**: Provide services to multiple VPCs within your organization.
- **SaaS provider model**: Offer your application to customers without internet exposure.
- **Hybrid cloud architecture**: Connect on-premises networks to AWS services.
- **Compliance requirements**: Meet regulatory requirements for private connectivity.
- **Multi-account architecture**: Connect services across different AWS accounts.
- **Service provider model**: Expose your services to other AWS customers.
- **Financial data processing**: Process sensitive financial data without internet exposure.

## Benefits

- **Enhanced security**: Eliminate exposure of your traffic to the public internet.
- **Simplified network architecture**: No need for complex firewalls, internet gateways, or NAT devices.
- **Improved compliance**: Help meet regulatory requirements for private data connectivity.
- **Reduced data transfer costs**: Potential cost savings for data transfer compared to internet-based connections.
- **Increased reliability**: Direct connections to services without internet dependencies.
- **Scalability**: Automatically scales with your traffic demands.
- **Service access control**: Fine-grained control over who can access your services.
- **Simplified service publishing**: Make your services available to other VPCs easily.

## Pricing

AWS PrivateLink pricing is based on:

- Hourly charges for each VPC endpoint or endpoint service
- Data processing charges for traffic flowing through the endpoints
- Network Load Balancer charges (for endpoint services)

Pricing varies by AWS region. There are no upfront costs or long-term commitments.