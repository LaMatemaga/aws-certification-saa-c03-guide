---
group:
  - technology
---
AWS Site-to-Site VPN creates a secure connection between your on-premises network or branch office site and your AWS Virtual Private Cloud (VPC). This service is fully managed by AWS and provides a cost-effective way to create encrypted tunnels for secure communication between your corporate network and AWS cloud resources.

## Key Features

- **IPsec encryption**: Industry-standard encryption for secure communications.
- **High availability**: Two VPN tunnels per connection for redundancy.
- **AWS managed service**: No need to manage VPN hardware or software.
- **Static and dynamic routing**: Support for static routes and dynamic BGP routing.
- **Accelerated VPN**: Improve performance with AWS Global Accelerator.
- **VPN CloudHub**: Connect multiple sites through AWS VPN.
- **IPv4 and IPv6 support**: Connect IPv4 and IPv6 networks.
- **Custom tunnel options**: Configure tunnel encryption, integrity algorithms, and more.
- **VPN monitoring**: Monitor connections with CloudWatch metrics.
- **VPN logging**: Log VPN connection activity.
- **Multiple VPN connections**: Support for multiple VPN connections per VPC.
- **Transit Gateway integration**: Connect VPNs to multiple VPCs through Transit Gateway.

## Connection Components

- **Virtual Private Gateway (VGW)**: The AWS endpoint for your VPN connection.
- **Transit Gateway**: Alternative AWS endpoint supporting higher bandwidth and more connections.
- **Customer Gateway**: Represents your on-premises VPN device.
- **VPN Connection**: The connection between your VGW/TGW and customer gateway.
- **VPN Tunnels**: Two encrypted tunnels for each VPN connection for redundancy.

## Routing Options

- **Static routing**: Manually specify network routes.
- **Dynamic routing (BGP)**: Automatically exchange routing information using Border Gateway Protocol.
- **Route propagation**: Automatically propagate routes to VPC route tables.
- **Route-based VPN**: Create tunnels as network interfaces for more flexible routing.
- **Policy-based VPN**: Define which traffic should be encrypted based on policies.

## VPN Types

- **AWS Site-to-Site VPN**: Connect on-premises network to AWS.
- **AWS Transit Gateway + Site-to-Site VPN**: Connect multiple VPCs and on-premises networks.
- **Software VPN**: Customer-managed VPN solution running on EC2.
- **AWS VPN CloudHub**: Hub-and-spoke model to connect multiple branch offices.
- **AWS Accelerated Site-to-Site VPN**: Higher performance VPN using edge locations.

## Common Use Cases

- **Hybrid cloud connectivity**: Connect on-premises data centers to AWS.
- **Branch office connectivity**: Connect remote offices to your AWS environment.
- **Backup and disaster recovery**: Secure connection for data replication.
- **Application migration**: Secure connectivity during cloud migration.
- **Temporary connectivity**: Establish secure connection until a Direct Connect can be provisioned.
- **Multi-site connectivity**: Connect multiple sites to AWS via CloudHub.
- **Development and testing**: Provide developers secure access to cloud resources.
- **Cost-effective secure connectivity**: Alternative to more expensive dedicated connections.

## Benefits

- **Security**: Encrypted connection between your network and AWS.
- **Reliability**: Redundant tunnels and automatic failover.
- **Managed service**: No need to manage VPN hardware or software.
- **Flexibility**: Compatible with most VPN devices and software.
- **Cost-effective**: Lower cost compared to dedicated connections.
- **Quick to deploy**: Can be set up in minutes.
- **Scalability**: Support for high-bandwidth requirements.
- **Integration**: Works with other AWS networking services.

## Pricing

AWS Site-to-Site VPN pricing is based on:

- Hourly charge for each VPN connection
- Data transfer charges for data sent over the VPN connection

Accelerated VPN incurs additional charges. There are no upfront costs or long-term commitments.