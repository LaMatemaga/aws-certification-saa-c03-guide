---
group:
  - technology
---
Amazon Virtual Private Cloud (Amazon VPC) is a service that lets you launch AWS resources in a logically isolated virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways.

## Key Features

- **Isolated environment**: Create a logically isolated section of the AWS Cloud.
- **IP addressing**: Define your own IPv4 and IPv6 address ranges.
- **Subnets**: Create public and private subnets within your VPC.
- **Routing**: Configure route tables to control traffic flow.
- **Security groups**: Act as virtual firewalls to control inbound and outbound traffic.
- **Network ACLs**: Provide stateless filtering of inbound and outbound traffic.
- **Gateways**: Internet gateways, NAT gateways, and private gateways for connectivity.
- **VPC peering**: Connect VPCs within or across AWS accounts.
- **VPC endpoints**: Privately connect to supported AWS services without internet exposure.
- **Flow logs**: Capture IP traffic information for network monitoring.
- **Traffic mirroring**: Copy network traffic for deep packet inspection.
- **PrivateLink**: Access services privately across AWS accounts and VPCs.
- **Transit Gateway**: Simplify network connectivity between VPCs and on-premises networks.
- **IPv6 support**: Full support for IPv6 addressing.
- **Reachability Analyzer**: Analyze network paths between resources.
- **Network Manager**: Centrally manage networks across accounts and regions.

## VPC Components

- **Subnets**: Segments of a VPC's IP address range where you can place groups of isolated resources.
- **Route tables**: Control traffic leaving subnets.
- **Internet gateway**: Allows communication between resources in your VPC and the internet.
- **NAT gateway**: Enables instances in a private subnet to connect to the internet.
- **VPC endpoints**: Connect to AWS services privately without using public IPs.
- **Security groups**: Virtual firewalls for instances to control inbound and outbound traffic.
- **Network ACLs**: Stateless firewalls for subnets.
- **DHCP option sets**: Control DHCP settings for your VPC.
- **Elastic IPs**: Static IPv4 addresses for dynamic cloud computing.
- **VPC sharing**: Share subnets with other AWS accounts.
- **Elastic network interfaces**: Virtual network interfaces that can be attached to instances.
- **Prefix lists**: Groups of CIDR blocks for simplified management.

## Connectivity Options

- **Internet gateway**: Connect to the public internet.
- **NAT gateway/instance**: Allow private resources to access the internet.
- **VPC peering**: Connect VPCs directly.
- **Transit Gateway**: Connect multiple VPCs and on-premises networks.
- **VPN connections**: Secure connection to on-premises networks.
- **Direct Connect**: Dedicated physical connection to AWS.
- **VPC endpoints**: Private connections to AWS services.
- **PrivateLink**: Private connections to services in other VPCs.
- **Egress-only internet gateway**: IPv6 outbound connections only.

## Security Features

- **Security groups**: Instance-level, stateful firewall.
- **Network ACLs**: Subnet-level, stateless firewall.
- **Flow logs**: Capture network traffic metadata.
- **Traffic mirroring**: Copy and analyze network traffic.
- **Private subnets**: Isolate resources from direct internet access.
- **Network segmentation**: Isolate workloads within your VPC.
- **VPC endpoints**: Access AWS services without internet exposure.
- **IAM policies**: Control who can manage VPC resources.
- **Private DNS**: Use custom DNS names within your VPC.

## Common Use Cases

- **Hosting web applications**: Build multi-tier web applications.
- **Extending on-premises networks**: Create hybrid architectures.
- **Disaster recovery**: Create backup environments in the cloud.
- **Data processing**: Run large-scale data processing workloads.
- **Development and testing**: Create isolated environments for development.
- **Security and compliance**: Meet regulatory requirements with network isolation.
- **SaaS applications**: Deploy software as a service applications.
- **Microservices**: Deploy containerized microservices in isolated networks.
- **Big data processing**: Process large datasets in secure environments.

## Benefits

- **Security**: Control over your network configuration and traffic isolation.
- **Control**: Fine-grained control over resource access and connectivity.
- **Customization**: Design your network to meet specific requirements.
- **Scalability**: Scale your network as your needs grow.
- **Hybrid capability**: Connect to on-premises infrastructure.
- **Cost-effective**: No additional charges for VPC itself.
- **Integration**: Works seamlessly with other AWS services.
- **Compliance**: Meet regulatory requirements with network isolation.

## Pricing

Amazon VPC itself has no additional charges. You pay only for resources you create to support your VPC, such as:

- NAT gateways
- VPC endpoints
- Traffic mirroring
- Flow logs storage
- VPN connections
- Transit Gateway

Standard charges for data transfer apply for traffic entering and leaving your VPC.