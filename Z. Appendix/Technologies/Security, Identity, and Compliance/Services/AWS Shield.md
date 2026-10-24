---
group:
  - technology
---
AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS against external threats that affect availability and performance. AWS offers two tiers of protection: AWS Shield Standard, which is available to all AWS customers at no additional cost, and AWS Shield Advanced, which provides enhanced DDoS protection for more sensitive applications.

## Service Tiers

### AWS Shield Standard

Automatically included at no additional cost for all AWS customers:

- **Always-on detection and automatic mitigations**: Protection against common and frequently occurring DDoS attacks.
- **Layer 3 and Layer 4 protection**: Defense against network and transport layer attacks.
- **Global threat monitoring**: AWS constantly monitors global traffic patterns.
- **SYN/UDP floods protection**: Protection against common flood attacks.
- **Reflection attacks protection**: Protects against various reflection attacks.
- **Infrastructure layer protection**: Protects AWS resources like EC2, ELB, CloudFront, and Route 53.

### AWS Shield Advanced

Subscription service for higher levels of protection and support:

- **Enhanced protection**: Specialized protection for EC2, ELB, CloudFront, Global Accelerator, and Route 53.
- **Application layer protection**: Integration with AWS WAF at no additional cost.
- **Real-time visibility and notifications**: Access to real-time metrics and DDoS events.
- **24/7 DDoS Response Team (DRT)**: Direct access to AWS DDoS experts.
- **DDoS cost protection**: Reimbursement for scaling expenses during DDoS attacks.
- **Protected resource monitoring**: Custom protection of specific resources.
- **Health-based detection**: Proactive detection based on health of your applications.
- **Advanced event diagnostics**: Detailed diagnostics during active attacks.
- **Protection groups**: Simplify protection of multiple resources.

## Attack Types Mitigated

- **Volumetric attacks**: Flood attacks that saturate bandwidth.
- **TCP SYN floods**: Attacks that exhaust server connection state tables.
- **UDP reflection attacks**: Attacks using spoofed source addresses.
- **DNS query floods**: High volume DNS query attacks.
- **HTTP floods/cache-busting attacks**: Application layer request floods (with Advanced tier).
- **Resource exhaustion attacks**: Attacks targeting resource limitations.

## AWS Services Protected

- **Amazon EC2**: Compute instances
- **Elastic Load Balancing**: Load balancers
- **Amazon CloudFront**: Content delivery network
- **AWS Global Accelerator**: Network acceleration service
- **Amazon Route 53**: DNS service

## Common Use Cases

- **Website and web application protection**: Protect customer-facing websites from DDoS attacks.
- **API protection**: Safeguard API endpoints from DDoS attacks.
- **Gaming infrastructure**: Protect gaming servers and infrastructure.
- **Enterprise applications**: Protect business-critical applications.
- **IoT platforms**: Protect platforms connecting numerous IoT devices.
- **SaaS applications**: Protect software-as-a-service offerings.
- **Financial services platforms**: Protect sensitive financial applications.
- **E-commerce platforms**: Ensure availability of online shopping experiences.

## Benefits

- **Always-on protection**: Continuous monitoring and protection.
- **Cost-effective**: Standard tier included at no additional cost.
- **Seamless integration**: Works automatically with AWS services.
- **Specialized support**: Access to DDoS experts with Advanced tier.
- **Cost protection**: Financial protection from scaling during attacks.
- **Real-time visibility**: Metrics and alerts for attack detection.
- **Application layer protection**: Integration with AWS WAF for deeper protection.

## Pricing

- **AWS Shield Standard**: Included at no additional cost for all AWS customers.
- **AWS Shield Advanced**: Subscription-based pricing with:
    - Monthly fee per organization
    - Additional monthly fee per protected resource
    - 1-year commitment required
    - Includes AWS WAF at no additional cost for protected resources