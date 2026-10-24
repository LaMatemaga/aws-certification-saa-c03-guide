---
group:
  - technology
---
AWS Transit Gateway is a network transit hub that connects VPCs and on-premises networks through a central hub. This service simplifies network architecture, improves connectivity, and enhances security by acting as a cloud router - each connection is only made once to the Transit Gateway, which manages all routing between connected networks.

## Key Features

- **Centralized connectivity**: Connect multiple VPCs and on-premises networks through a single gateway.
- **Simplified architecture**: Replace complex peering relationships with a hub-and-spoke model.
- **Regional routing**: Efficient routing within an AWS region.
- **Multi-region support**: Connect Transit Gateways across regions using peering.
- **Transitive routing**: Enable communication between any connected network.
- **Bandwidth**: Support for up to 100 Gbps bandwidth per Availability Zone.
- **Route tables**: Multiple route tables for granular control over network traffic.
- **Attachments**: Connect VPCs, VPNs, Direct Connect gateways, and other Transit Gateways.
- **Multicast support**: Distribute one-to-many traffic over your network.
- **Network Manager**: Visual interface to manage and monitor your global network.
- **VPC sharing**: Centrally manage shared VPCs across accounts.
- **Flow logs**: Capture network flow information for monitoring and analysis.
- **Equal-cost multi-path routing (ECMP)**: Load balancing across multiple network paths.
- **Cross-account sharing**: Share resources with AWS Resource Access Manager.

## Attachment Types

- **VPC attachments**: Connect Amazon VPCs.
- **VPN attachments**: Connect on-premises networks via Site-to-Site VPN.
- **Direct Connect gateway attachments**: Connect on-premises networks via AWS Direct Connect.
- **Transit Gateway peering attachments**: Connect Transit Gateways in different regions.
- **Connect attachments**: Integrate with third-party SD-WAN solutions.

## Routing Features

- **Transit Gateway route tables**: Control traffic flow between attachments.
- **Route propagation**: Automatically share routes from attachments.
- **Static routes**: Manually define specific routes.
- **Blackhole routes**: Drop traffic to specific destinations.
- **Route priority**: Control route preference with prefix lists.
- **Route analysis**: Analyze how traffic will be routed.
- **Multipath routing**: Multiple equal-cost routes for the same destination.
- **Dynamic routing**: Support for BGP for dynamic route exchange.

## Common Use Cases

- **VPC consolidation**: Simplify connectivity between multiple VPCs.
- **Hybrid cloud architecture**: Connect on-premises networks to multiple VPCs.
- **Centralized network control**: Manage network topology from a central point.
- **Shared services**: Access shared services across multiple VPCs.
- **Multi-account architecture**: Connect VPCs across different AWS accounts.
- **Multi-region connectivity**: Connect resources across AWS regions.
- **Network segmentation**: Create isolated network segments for security.
- **Disaster recovery**: Establish redundant network connections.
- **Global network management**: Manage global networks through a single interface.

## Benefits

- **Simplified architecture**: Replace complex peering connections with a hub-and-spoke model.
- **Reduced operational overhead**: Manage fewer connections and configurations.
- **Enhanced security**: Centralized control over network traffic and security policies.
- **Improved scalability**: Easily add new VPCs and networks as your needs grow.
- **Increased bandwidth**: Support for high-bandwidth requirements.
- **Cost reduction**: Potentially lower costs compared to multiple individual connections.
- **Flexible routing**: Fine-grained control over traffic flow.
- **Consolidated billing**: Simplified billing for network traffic.

## AWS Network Manager

- **Global view**: Visualize your entire network infrastructure.
- **Monitoring**: Monitor the health and performance of your network.
- **Event tracking**: Track changes and events in your network.
- **Route analysis**: Analyze routing paths through your network.
- **Geographic mapping**: View your network on a geographic map.
- **Integration with CloudWatch**: Access detailed metrics and logs.

## Pricing

AWS Transit Gateway pricing is based on:

- Hourly charge for each Transit Gateway attachment
- Data processing charges for traffic flowing through the Transit Gateway
- Additional charges for Transit Gateway peering and Connect attachments

Pricing varies by AWS region. There are no upfront costs or long-term commitments.