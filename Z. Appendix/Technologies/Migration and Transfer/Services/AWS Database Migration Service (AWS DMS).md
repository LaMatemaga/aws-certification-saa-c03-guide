---
group:
  - technology
---
AWS Application Migration Service (AWS MGN) is a highly automated lift-and-shift solution that simplifies, expedites, and reduces the cost of migrating applications to AWS. It enables organizations to quickly lift-and-shift physical, virtual, or cloud servers without compatibility issues, performance disruption, or long cutover windows.

## Key Features

- **Block-level replication**: Continuous, asynchronous block-level replication for minimal impact on source servers.
- **Automated machine conversion**: Automatically converts source servers to run natively on AWS.
- **Non-disruptive testing**: Test migrated servers without disrupting operations of the source servers.
- **Large-scale migrations**: Support for migrations involving thousands of servers.
- **Broad compatibility**: Support for a wide range of operating systems, databases, and applications.
- **Application-agnostic migration**: Works regardless of application types being migrated.
- **Minimal downtime**: Short cutover windows to minimize application downtime.
- **Staged migrations**: Test before cutover to ensure applications work correctly on AWS.
- **Centralized management**: Track and manage all migrations through a single console.
- **Post-launch validation**: Verify successful migrations with automated testing.
- **Secure data transfer**: Encrypted data replication between source and target environments.
- **API access**: Programmatic access to automate and integrate with existing tools.

## Migration Process

1. **Initialize**: Install replication agents on source servers.
2. **Replicate**: Continuously replicate server data to AWS.
3. **Launch test instances**: Launch and test applications on AWS without disrupting source servers.
4. **Define launch settings**: Configure launch templates for final cutover.
5. **Cutover**: Perform final synchronization and launch production instances on AWS.
6. **Post-cutover operations**: Validate migrated servers and terminate temporary resources.

## Supported Source Platforms

- **Operating systems**: Windows and most Linux distributions.
- **Server types**: Physical servers, virtual machines, or cloud servers.
- **Virtualization platforms**: VMware, Hyper-V, Azure VMs, Google Cloud VMs, and others.
- **Source environments**: On-premises data centers, colocation facilities, other cloud providers.

## Common Use Cases

- **Data center exit**: Migrate from on-premises data centers to AWS.
- **Hardware refresh**: Avoid capital expenditure on new hardware by migrating to AWS.
- **Cloud-to-cloud migration**: Move workloads from other cloud providers to AWS.
- **Disaster recovery**: Use replication capabilities as part of a disaster recovery strategy.
- **Consolidation projects**: Consolidate multiple data centers into AWS.
- **Large-scale migrations**: Migrate hundreds or thousands of servers efficiently.
- **Legacy application migration**: Move legacy applications to AWS without code changes.
- **M&A integration**: Integrate acquired company IT assets into AWS environment.

## Integration with AWS Services

- **AWS Migration Hub**: Track migration progress centrally.
- **AWS Application Discovery Service**: Discover applications to plan migrations.
- **Amazon EC2**: Target for migrated servers.
- **Amazon EBS**: Storage for migrated server data.
- **AWS Systems Manager**: Manage servers post-migration.
- **AWS Identity and Access Management**: Control access to migration resources.
- **Amazon CloudWatch**: Monitor migration processes.
- **AWS CloudFormation**: Automate infrastructure provisioning.

## Benefits

- **Simplified migration**: Automate complex migration tasks to reduce effort.
- **Minimal downtime**: Continuous replication minimizes cutover windows.
- **Reduced cost**: Lower migration cost compared to traditional methods.
- **Accelerated migration**: Speed up migration projects with automation.
- **Reduced risk**: Test before cutover to verify application functionality.
- **No specialized expertise needed**: User-friendly interface for migration operations.
- **Application-agnostic**: Works with virtually any application without modification.
- **Scalability**: Capable of handling migrations of any size.

## Pricing

AWS Application Migration Service pricing is based on:

- Data storage for replication (EBS snapshots)
- Number of servers being migrated
- Duration of replication

The service follows a pay-as-you-go model with no upfront costs or commitments. The actual migration cutover is free, and you only pay for the AWS resources used during testing and replication.