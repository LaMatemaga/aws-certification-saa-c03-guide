---
group:
  - technology
---
Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses. It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones, improving availability and fault tolerance.

## Load Balancer Types

### Application Load Balancer (ALB)

Operates at the application layer (Layer 7):

- **HTTP/HTTPS traffic routing**: Content-based routing for HTTP/HTTPS applications.
- **Path-based routing**: Route traffic based on URL path.
- **Host-based routing**: Route traffic based on host headers.
- **Query string parameters**: Route based on query string parameters.
- **HTTP header-based routing**: Route traffic based on HTTP headers.
- **Source IP address-based routing**: Route based on client IP address.
- **Container integration**: Native integration with ECS and EKS.
- **WebSockets support**: Maintain long-running connections.
- **HTTP/2 support**: Improved performance for modern web applications.
- **Authentication integration**: Authenticate users through identity providers.
- **Fixed response**: Return a custom HTTP response directly.
- **Redirects**: Configure redirects from one URL to another.

### Network Load Balancer (NLB)

Operates at the transport layer (Layer 4):

- **Ultra-high performance**: Handle millions of requests per second.
- **Low latency**: Extremely low latency for performance-sensitive applications.
- **Static IP addresses**: One static IP address per Availability Zone.
- **Elastic IP support**: Bring your own Elastic IPs.
- **Preserve source IP address**: Client IP addresses are preserved.
- **UDP protocol support**: Support for applications using UDP protocol.
- **TCP preservation**: Maintain TCP connections to servers.
- **TLS termination**: Offload SSL/TLS encryption/decryption.
- **PrivateLink support**: Enable services for private access across VPCs.
- **VPC endpoint services**: Expose your applications as VPC endpoint services.

### Gateway Load Balancer (GWLB)

Operates at the network layer (Layer 3):

- **Transparent network gateway**: Intercept traffic for inspection.
- **Load balancing for virtual appliances**: Distribute traffic across security appliances.
- **Scale appliances**: Easily scale security appliances like firewalls.
- **Health monitoring**: Monitor appliance health and route around failures.
- **GENEVE protocol**: Uses the GENEVE protocol for encapsulation.
- **Preserve traffic information**: Maintains source and destination information.

### Classic Load Balancer (CLB)

Legacy load balancer (not recommended for new applications):

- **Basic Layer 4/7 load balancing**: For applications built within the EC2-Classic network.
- **Legacy support**: Maintains compatibility with EC2-Classic.

## Common Features Across Load Balancers

- **Health checks**: Monitor the health of registered targets.
- **High availability**: Deploy across multiple Availability Zones.
- **Security groups**: Control traffic to and from your load balancer.
- **Encryption**: TLS termination and management.
- **CloudWatch integration**: Monitoring and logging capabilities.
- **AWS WAF integration**: Web application firewall integration (ALB only).
- **AWS Shield integration**: DDoS protection.
- **Cross-zone load balancing**: Distribute traffic evenly across all registered targets.
- **Connection draining**: Allow existing connections to complete before deregistering targets.
- **Auto Scaling integration**: Automatically adjust capacity based on demand.
- **AWS Certificate Manager integration**: Simple certificate management.

## Common Use Cases

- **Web applications**: Distribute traffic to web servers.
- **Microservices architecture**: Route traffic between microservices.
- **Container-based applications**: Load balance containerized applications.
- **High availability architecture**: Improve application availability.
- **Security appliance scaling**: Scale third-party security appliances (GWLB).
- **TCP/UDP applications**: Load balance non-HTTP applications (NLB).
- **API services**: Distribute API requests across backend services.
- **Blue/green deployments**: Facilitate zero-downtime deployments.
- **A/B testing**: Direct traffic to different application versions.

## Benefits

- **High availability**: Distribute traffic across multiple targets in multiple zones.
- **Automatic scaling**: Handles varying loads without manual intervention.
- **Security**: Integrate with security features like AWS WAF and Shield.
- **Operational monitoring**: Detailed metrics and logging capabilities.
- **Hybrid connectivity**: Support for on-premises targets (with AWS Outposts).
- **Health checks**: Automatic detection and routing around unhealthy targets.
- **Cost-effective**: No upfront commitment, pay only for what you use.
- **Managed service**: AWS handles maintenance, upgrades, and high availability.

## Pricing

Elastic Load Balancing pricing is based on:

- Hourly charges for each running load balancer
- LCU (Load Balancer Capacity Units) for ALB and GWLB
- Number of new TCP/UDP connections for NLB
- Data processing charges

Pricing varies by AWS region and load balancer type. There are no upfront costs or long-term commitments.