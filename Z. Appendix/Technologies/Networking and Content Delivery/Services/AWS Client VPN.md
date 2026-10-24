---
group:
  - technology
---
AWS Client VPN is a fully managed, elastic VPN service that enables secure access to AWS resources and on-premises networks. It provides a secure and seamless way for remote users to connect to AWS and on-premises resources using an OpenVPN-based VPN client.

## Key Features

- **Managed service**: Fully managed by AWS with automatic scaling and high availability.
- **Secure connections**: Encrypted connections using TLS to protect data in transit.
- **Multi-authentication options**: Supports Active Directory authentication, mutual authentication, and federated authentication via SAML.
- **Split-tunnel support**: Allow specific traffic to bypass the VPN tunnel.
- **Client connectivity**: Compatible with standard OpenVPN clients.
- **Access control**: Fine-grained control over network access using security groups and network ACLs.
- **Connection logging**: Optional CloudWatch logs for connection events.
- **Self-service portal**: Provide users with a self-service portal for downloading VPN client configurations.
- **IPv4 and IPv6 support**: Connect to both IPv4 and IPv6 resources.
- **Client connection handler**: Control the maximum number of connections per client.

## Connection Methods

- **User-based authentication**:
    - Active Directory authentication
    - SAML-based federated authentication
    - Mutual certificate authentication
- **Client types**:
    - AWS Client VPN desktop application
    - Third-party OpenVPN clients
    - AWS provided client configurations

## Common Use Cases

- **Remote workforce access**: Provide secure remote access to corporate resources.
- **Contractor and partner access**: Grant temporary access to third parties.
- **Disaster recovery**: Ensure business continuity with secure remote access.
- **Site replacement**: Replace traditional VPN hardware with a cloud-based solution.
- **Multi-region access**: Connect to resources across different AWS regions.
- **Hybrid cloud access**: Access both cloud and on-premises resources through a single connection.
- **Mobile workforce**: Support employees who need to work from varying locations.
- **Development and test environments**: Provide developers with secure access to development environments.

## Integration with AWS Services

- **Amazon VPC**: Connect to VPC resources.
- **AWS Transit Gateway**: Access multiple VPCs through a single connection.
- **AWS Directory Service**: Integrate with Active Directory for authentication.
- **Amazon CloudWatch**: Monitor VPN connection metrics and logs.
- **AWS CloudTrail**: Audit API calls related to VPN configuration.
- **AWS IAM**: Control access to VPN configuration.

## Benefits

- **Simplified management**: No need to deploy, manage, or scale VPN infrastructure.
- **Cost-effective**: Pay only for what you use with no upfront investments.
- **High availability**: Automatically distributed across multiple Availability Zones.
- **Secure access**: Encrypted connections with multiple authentication options.
- **Scalability**: Automatically scales to support growing numbers of users.
- **Consistent experience**: Provide a consistent access experience to all users.
- **Reduced operational overhead**: No need to maintain VPN appliances.

## Pricing

AWS Client VPN pricing is based on:

- Hourly fee for each Client VPN endpoint association
- Per-connection fee charged hourly for each active connection

There are no upfront commitments, and you only pay for active endpoint associations and connections. Standard data transfer charges also apply.