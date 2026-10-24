---
group:
  - technology
---
AWS Application Discovery Service helps you plan your migration to the AWS cloud by collecting usage and configuration data about your on-premises servers and applications. It provides detailed information about your data center inventory, application dependencies, and resource utilization, which is essential for effective migration planning.

## Key Features

- **Agentless discovery**: Collect information without installing agents using VMware vCenter.
- **Agent-based discovery**: Gather detailed system configuration, performance, running processes, and network dependencies using lightweight agents.
- **Data exploration and visualization**: Explore and analyze discovered data through the AWS Migration Hub console.
- **Application dependency mapping**: Identify connections between applications and servers to plan migration groups.
- **Data export**: Export discovery data for analysis in Amazon Athena or other tools.
- **Continuous data collection**: Gather utilization data over time to properly size AWS resources.
- **Secure data handling**: Encrypted data collection and transmission.
- **Integration with AWS Migration Hub**: Centralized tracking of discovered servers and applications.
- **API access**: Programmatic access to discovery data.

## Discovery Methods

### Agentless Discovery (Application Discovery Service Agentless Collector)

- **Deployment method**: OVA file deployed on VMware vCenter.
- **Data collected**: Basic host and VM information, hardware configuration, network connections.
- **Benefits**: Quick setup, minimal impact on environment.
- **Limitations**: Limited detailed information about applications running on servers.

### Agent-based Discovery (AWS Application Discovery Agent)

- **Deployment method**: Lightweight agent installed on Windows and Linux servers.
- **Data collected**: System configuration, utilization metrics, network connections, processes, performance data.
- **Benefits**: Detailed information about applications, dependencies, and performance.
- **Limitations**: Requires agent installation and management.

## Data Types Collected

- **Server inventory data**: OS, hostnames, IP addresses, MAC addresses.
- **Hardware configuration**: CPU, memory, disk configurations.
- **Resource utilization**: CPU, memory, disk I/O, and network throughput over time.
- **Network connections**: Inbound and outbound network connections between servers.
- **Application components**: Running processes and system services.
- **Application dependencies**: Communication patterns between applications and servers.
- **Time-series performance data**: Historical performance metrics.

## Common Use Cases

- **Migration planning**: Gather information needed for effective AWS migration planning.
- **Application dependency mapping**: Understand application relationships to plan migration waves.
- **Right-sizing**: Collect utilization data to properly size AWS resources.
- **TCO analysis**: Export data to calculate total cost of ownership in AWS.
- **Application portfolio assessment**: Categorize applications for rehost, replatform, refactor decisions.
- **Compliance documentation**: Document existing environment for compliance requirements.
- **Data center inventory**: Catalog existing servers and applications.
- **Modernization planning**: Identify applications for modernization during migration.

## Integration with AWS Services

- **AWS Migration Hub**: Centralize tracking of discovered data and migration planning.
- **AWS Database Migration Service**: Information to support database migration planning.
- **AWS Application Migration Service**: Server details to assist in replication planning.
- **Amazon Athena**: Analyze exported data using SQL queries.
- **Amazon S3**: Store collected data securely.

## Benefits

- **Accelerated migration planning**: Reduce time required to collect migration planning data.
- **Reduced risk**: Identify application dependencies to prevent migration failures.
- **Data-driven decisions**: Make informed decisions based on actual usage data.
- **Optimized costs**: Right-size AWS resources based on actual utilization data.
- **Simplified discovery**: Automate the process of cataloging servers and applications.
- **Comprehensive view**: Gain visibility into your entire IT environment.
- **Centralized data**: Access all discovery data from a single location.

## Pricing

AWS Application Discovery Service pricing is based on:

- No charge for using the service
- Standard data transfer and storage charges may apply for related AWS services

The service itself is offered at no additional cost, making it an economical way to plan your AWS migration strategy.