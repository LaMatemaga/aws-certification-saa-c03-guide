---
group:
  - technology
---
AWS Direct Connect is a cloud service that establishes a dedicated network connection from your premises to AWS. Using AWS Direct Connect, you can establish private connectivity between AWS and your datacenter, office, or colocation environment, which in many cases can reduce your network costs, increase bandwidth throughput, and provide a more consistent network experience than internet-based connections.

## Key Features

- **Dedicated connections**: Establish 1, 10, 100, or 400 Gbps dedicated network connections.
- **Hosted connections**: Get connections through AWS Direct Connect Partners with lower bandwidth options.
- **Private virtual interfaces (VIFs)**: Connect directly to your Amazon VPC using private IP addresses.
- **Public virtual interfaces**: Connect to AWS public services like S3 and DynamoDB without traversing the internet.
- **Transit virtual interfaces**: Connect to AWS Transit Gateway for simplified network management.
- **Direct Connect gateways**: Connect to multiple VPCs across different AWS regions.
- **LAG (Link Aggregation Groups)**: Combine multiple connections for higher bandwidth and redundancy.
- **MAC Security (MACsec)**: Layer 2 encryption for enhanced security.
- **BFD (Bidirectional Forwarding Detection)**: Fast detection of network failures.
- **Jumbo frames**: Support for frames up to 9001 MTU for increased network efficiency.
- **BGP routing**: Dynamic routing using Border Gateway Protocol.
- **BGP communities**: Control routing behavior using BGP community tags.

## Connection Types

- **Dedicated connections**:
    - Physical Ethernet connections dedicated to a single customer
    - Available in 1, 10, 100, and 400 Gbps ports
    - Ordered through AWS and available at AWS Direct Connect locations
- **Hosted connections**:
    - Connections facilitated through AWS Direct Connect Partners
    - Available in various capacities from 50 Mbps to 10 Gbps
    - Ordered through AWS Direct Connect Partners

## Resiliency Models

- **Maximum resiliency**: Multiple connections at multiple Direct Connect locations with redundant customer devices.
- **High resiliency**: Multiple connections at multiple Direct Connect locations.
- **Development and test**: Single connection at a single Direct Connect location.
- **SiteLink**: Connection between your sites through AWS Direct Connect locations without traversing the AWS network.

## Common Use Cases

- **Hybrid cloud architecture**: Connect on-premises infrastructure with AWS cloud resources.
- **Large dataset migration**: Transfer large amounts of data directly to AWS.
- **Real-time data processing**: Reduce latency for time-sensitive applications.
- **Consistent network performance**: Establish reliable, consistent network performance.
- **Bandwidth-intensive applications**: Support applications requiring high throughput.
- **Regulatory compliance**: Meet compliance requirements for private network connections.
- **Reduce network costs**: Potentially reduce egress costs compared to internet-based connections.
- **Disaster recovery**: Establish reliable connections to AWS for disaster recovery scenarios.

## Integration with AWS Services

- **Amazon VPC**: Connect directly to your private VPC resources.
- **AWS Transit Gateway**: Connect to multiple VPCs through a single Direct Connect connection.
- **AWS PrivateLink**: Access AWS services privately without using public endpoints.
- **AWS Site-to-Site VPN**: Combine with VPN for encrypted communications.
- **Amazon Route 53 Resolver**: Utilize private DNS resolution.
- **AWS Global Accelerator**: Improve performance for applications accessed globally.

## Benefits

- **Reduced costs**: Potentially lower data transfer costs compared to internet-based connections.
- **Increased bandwidth**: Support for high-bandwidth workloads with up to 400 Gbps connections.
- **Consistent performance**: More reliable and consistent network performance.
- **Private connectivity**: Direct private connectivity to AWS services without internet exposure.
- **Scalable**: Scale bandwidth to meet your needs.
- **Compliance**: Meet regulatory requirements with private connections.
- **Hybrid cloud enablement**: Seamlessly integrate on-premises and cloud environments.

## Pricing

AWS Direct Connect pricing is based on:

- Port hourly charges (for dedicated connections)
- Per-hour charges based on capacity (for hosted connections)
- Data transfer out charges (typically lower than internet data transfer rates)
- Additional charges for Direct Connect gateways and SiteLink

Pricing varies by AWS region and connection type. There are no minimum commitments for hosted connections, but dedicated connections have a minimum commitment.