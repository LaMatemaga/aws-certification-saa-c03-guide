---
group:
  - technology
---
AWS Network Firewall is a managed service that makes it easy to deploy essential network protections for all of your Amazon Virtual Private Clouds (VPCs). It provides stateful firewall capabilities with built-in intrusion prevention system (IPS) features to help protect your network from unauthorized traffic and malicious activities.

## Key Features

- **Stateful inspection**: Monitor and control traffic flows based on connection state.
- **Intrusion prevention**: Built-in intrusion prevention functionality to detect and block exploit attempts.
- **Protocol awareness**: Deep packet inspection for common protocols.
- **Network traffic filtering**: Filter traffic based on rules and patterns.
- **Domain filtering**: Allow or deny outbound connections based on domains.
- **Custom rule engines**: Create custom rule sets for your specific security needs.
- **Rule groups management**: Create, manage, and reuse collections of rules.
- **Centralized deployment**: Deploy and manage firewalls across multiple VPCs.
- **High availability**: Automatic deployment across multiple Availability Zones.
- **Logging capabilities**: Log network traffic for security analysis and compliance.
- **Integration with AWS Firewall Manager**: Centrally manage firewalls across accounts.

## Rule Types

- **Stateful rules**:
    - 5-tuple rules (source IP, destination IP, source port, destination port, protocol)
    - Domain filtering rules
    - Suricata-compatible IPS rules
- **Stateless rules**:
    - Pass, drop, or forward traffic based on source/destination, ports, and protocols
    - Processing happens before stateful rule inspection

## Deployment Options

- **Distributed deployment**: Deploy firewall endpoints in multiple subnets.
- **Centralized deployment**: Deploy in a dedicated inspection VPC.
- **Multi-account deployment**: Manage via AWS Firewall Manager across accounts.
- **Custom traffic routing**: Use with AWS Transit Gateway for customized network architectures.

## Traffic Inspection Capabilities

- **Protocol decoders**: Deep packet inspection for many protocols.
- **Pattern matching**: Match traffic against known malicious patterns.
- **Domain filtering**: Control outbound connections based on fully qualified domain names.
- **TLS inspection**: Decrypt and inspect TLS traffic (requires certificate integration).
- **Application layer filtering**: Apply rules at the application layer.
- **Protocol anomaly detection**: Identify non-standard protocol usage.

## Common Use Cases

- **VPC perimeter protection**: Protect VPCs from malicious traffic.
- **East-west traffic control**: Manage traffic between internal VPCs or subnets.
- **Outbound traffic filtering**: Control and monitor outbound connections.
- **Intrusion prevention**: Detect and block network attacks.
- **Compliance requirements**: Help meet compliance requirements for network security.
- **Network segmentation**: Enforce segmentation policies between network zones.
- **Malware detection**: Identify and block malware communication patterns.
- **Network visibility**: Gain insights into network traffic patterns.

## Benefits

- **Managed service**: No firewall infrastructure to deploy or manage.
- **Consistent protection**: Apply consistent protections across your VPCs.
- **Scalability**: Automatically scales with your network traffic.
- **High availability**: Deployed across multiple Availability Zones.
- **Integration**: Works with existing AWS services like VPC, Transit Gateway, and CloudWatch.
- **Cost-effective**: Pay for what you use with no upfront commitments.

## Pricing

AWS Network Firewall pricing is based on:

- Firewall endpoints deployed
- Volume of traffic inspected

There are no upfront commitments, and you only pay for what you use.