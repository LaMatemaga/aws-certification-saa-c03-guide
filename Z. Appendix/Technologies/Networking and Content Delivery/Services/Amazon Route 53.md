---
group:
  - technology
---
Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service designed to give developers and businesses a reliable and cost-effective way to route end users to Internet applications by translating domain names into IP addresses. Route 53 also offers domain name registration services, letting you purchase and manage domains directly within AWS.

## Key Features

- **Domain registration**: Register new domains and manage existing ones.
- **DNS service**: Translate domain names to IP addresses.
- **Health checking**: Monitor the health of your applications and resources.
- **Traffic flow**: Route users based on geolocation, latency, and availability.
- **Routing policies**: Multiple routing options for different use cases.
- **DNS firewall**: Protect your VPCs against DNS threats.
- **Resolver**: Recursive DNS service for your VPCs.
- **Private DNS**: DNS for your Amazon VPC.
- **DNSSEC**: Domain Name System Security Extensions support.
- **Query logging**: Analyze DNS queries made to your domains.
- **Auto naming**: Service discovery for cloud resources.
- **Global service**: Distributed across the world for high availability.
- **100% SLA**: The only AWS service with a 100% availability SLA.

## Routing Policies

- **Simple routing**: Route traffic to a single resource.
- **Weighted routing**: Route traffic to multiple resources in specified proportions.
- **Latency-based routing**: Route traffic to the AWS region with the lowest latency.
- **Failover routing**: Route traffic to a backup resource when the primary is unavailable.
- **Geolocation routing**: Route traffic based on the geographic location of users.
- **Geoproximity routing**: Route traffic based on the geographic location of resources.
- **Multi-value answer routing**: Return multiple values in response to DNS queries.
- **IP-based routing**: Route traffic based on users' IP addresses.

## Route 53 Resolver

- **Inbound Resolver**: Allow on-premises systems to resolve DNS records in your VPCs.
- **Outbound Resolver**: Allow your VPCs to resolve DNS records for on-premises domains.
- **Resolver Rules**: Control which DNS queries are forwarded.
- **Resolver DNS Firewall**: Block DNS queries made to known malicious domains.
- **Resolver Query Logging**: Log DNS queries made by resources in your VPCs.
- **Conditional Forwarding**: Forward specific domain queries to designated servers.

## Traffic Flow

- **Visual editor**: Create complex routing configurations with a visual editor.
- **Version control**: Save and manage multiple versions of routing configurations.
- **Geoproximity routing**: Route traffic based on the geographic proximity of users to resources.
- **Health check integration**: Automatically route around unhealthy endpoints.

## Common Use Cases

- **Domain registration**: Register and manage domain names.
- **Public DNS management**: Manage DNS records for public-facing websites and applications.
- **Private DNS management**: DNS for internal resources within VPCs.
- **High availability architecture**: Route traffic to healthy endpoints across regions.
- **Disaster recovery**: Automatically route traffic away from failed resources.
- **Global load balancing**: Distribute traffic globally to optimize performance.
- **Hybrid cloud DNS**: Connect on-premises DNS with AWS DNS.
- **Blue/green deployments**: Gradually shift traffic to new application versions.
- **Service discovery**: Automatically register and discover cloud resources.

## Benefits

- **High availability**: Distributed across the globe for maximum reliability.
- **Scalability**: Automatically handles high query volumes.
- **Integration**: Works seamlessly with other AWS services.
- **Security**: Robust security controls and DNSSEC support.
- **Flexibility**: Multiple routing policies for different requirements.
- **Simplicity**: Easy-to-use console and API.
- **Cost-effective**: Pay only for what you use.
- **Health-aware**: Integrates with health checks to route around failures.

## Pricing

Amazon Route 53 pricing is based on:

- Monthly charge for hosted zones
- Query charges for DNS queries
- Health check fees for monitored endpoints
- Traffic flow record charges
- Domain registration fees

Pricing varies by feature and usage. There are no upfront costs or long-term commitments.