---
group:
  - technology
---
AWS Global Accelerator is a networking service that improves the availability and performance of your applications for local and global users. It provides static IP addresses that act as a fixed entry point to your application endpoints in a single or multiple AWS Regions, such as Application Load Balancers, Network Load Balancers, EC2 instances, and elastic IP addresses.

## Key Features

- **Static anycast IP addresses**: Two static IP addresses that serve as fixed entry points to your applications.
- **Global network**: Traffic routed over AWS's global network rather than the public internet.
- **Automatic traffic routing**: Automatically routes traffic to the closest point of presence.
- **Health checks**: Continuous health checks to detect endpoint failures.
- **Failover**: Automatic failover between healthy endpoints in seconds.
- **Preserve client IP addresses**: Client source IP addresses are preserved for your applications.
- **TCP and UDP support**: Support for both TCP and UDP protocols.
- **Fine-grained traffic control**: Traffic dials to control the percentage of traffic to different endpoints.
- **Client affinity**: Direct all requests from a specific client to the same endpoint.
- **BYOIP support**: Bring your own IP addresses to Global Accelerator.
- **Security**: DDoS protection with AWS Shield.
- **Centralized management**: Single interface to manage global routing policies.

## Components

- **Static IP addresses**: Two static anycast IPv4 addresses (or bring your own).
- **Accelerator**: The main resource, which includes IP addresses, listener configuration, and endpoints.
- **Listeners**: Process inbound connections from clients based on ports and protocols.
- **Endpoint groups**: Logical groupings of endpoints in one or more AWS Regions.
- **Endpoints**: Resources to which Global Accelerator directs traffic, such as NLBs, ALBs, EC2 instances, or Elastic IPs.
- **Traffic dials**: Controls for managing traffic distribution to endpoint groups.

## How It Works

1. Global Accelerator provides you with two static IP addresses.
2. These IP addresses are anycast from AWS edge locations.
3. Traffic from users is routed to the nearest edge location via the AWS global network.
4. Within the AWS network, traffic is routed to your endpoints.
5. Health checks monitor your endpoints and reroute traffic in case of failures.
6. You can adjust traffic dials to control the percentage of traffic going to different regions.

## Common Use Cases

- **Multi-region applications**: Improve availability and failover for applications deployed across regions.
- **Gaming applications**: Reduce latency for global users with latency-sensitive gaming applications.
- **IoT applications**: Provide reliable connections for IoT devices worldwide.
- **Voice and video applications**: Enhance real-time communications with optimized routing.
- **Media delivery**: Accelerate media content delivery to global audiences.
- **Global APIs**: Improve performance for globally accessed APIs.
- **Disaster recovery**: Enable fast failover across regions during outages.
- **Migration to AWS**: Simplify migration by keeping the same IP addresses.

## Benefits

- **Improved availability**: Automatic health checks and failover improve application availability.
- **Enhanced performance**: Traffic routing over the AWS global network reduces internet congestion.
- **Global reach**: Easy deployment to a global audience without complex configurations.
- **Easy management**: Simple configuration for global traffic management.
- **Fixed entry point**: Static IP addresses simplify DNS and firewall configurations.
- **DDoS protection**: Integrated with AWS Shield for DDoS protection.
- **Fast failover**: Failover between endpoints in seconds rather than minutes.
- **Simplified multi-region deployment**: Easy to distribute traffic across multiple regions.

## Pricing

AWS Global Accelerator pricing is based on:

- Fixed hourly fee for each accelerator you set up
- Data transfer fee based on the amount of data transferred through the service

Premium pricing applies for traffic between certain geographic regions. There are no upfront costs or long-term commitments.