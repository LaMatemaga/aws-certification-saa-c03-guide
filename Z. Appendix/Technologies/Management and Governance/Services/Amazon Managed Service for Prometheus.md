---
group:
  - technology
---
Amazon Managed Service for Prometheus (AMP) is a serverless, Prometheus-compatible monitoring service for container metrics that makes it easier to securely monitor container environments at scale. It is a fully managed service that automatically scales the ingestion, storage, querying, and alerting of your metrics.

## Key Features

- **Serverless architecture**: No servers to manage or provision.
- **Prometheus compatibility**: Compatible with open-source Prometheus query language (PromQL).
- **Automatic scaling**: Scales with your metrics ingestion and query needs.
- **High availability**: Metrics replicated across multiple Availability Zones.
- **Long-term storage**: Store metrics for up to 150 days.
- **Alert manager**: Define and manage alerts based on metric conditions.
- **Rule evaluation**: Evaluate recording and alerting rules.
- **AWS authentication**: Secure access using IAM.
- **Cross-account data collection**: Collect metrics from multiple AWS accounts.
- **VPC endpoints**: Secure access within your VPC.
- **Metric collection APIs**: HTTP APIs for remote_write and query.
- **Workspaces**: Logical isolation of metrics data.
- **Custom and managed collectors**: Options for metrics collection.
- **Federation**: Query metrics from multiple sources.
- **Label-based security**: Control access using metric labels.

## Deployment Options

- **Direct ingestion**: Send metrics using the remote_write protocol.
- **AWS Distro for OpenTelemetry**: Collect and send metrics using ADOT.
- **Managed collectors**: AWS-managed collector service.
- **Self-managed collectors**: Run your own Prometheus servers as collectors.
- **Kubernetes integration**: Native integration with Amazon EKS.
- **Amazon ECS integration**: Collect metrics from ECS environments.
- **Amazon EC2 integration**: Monitor EC2 instances and workloads.
- **Cross-account collection**: Collect metrics across AWS accounts.
- **Cross-region collection**: Collect metrics from multiple AWS regions.

## Metrics Components

- **Metrics ingestion**: Push metrics via remote_write protocol.
- **Metrics storage**: Automated, scalable, high-availability storage.
- **Query processing**: Process PromQL queries efficiently.
- **Alert management**: Define, evaluate, and notify on alerts.
- **Rule evaluation**: Process recording and alerting rules.
- **Label management**: Organize metrics with labels.
- **Workspace management**: Isolate metrics in workspaces.
- **Access control**: Control access to metrics and APIs.
- **Data retention**: Configure retention periods for metrics.

## Common Use Cases

- **Container monitoring**: Monitor Kubernetes and container environments.
- **Microservices observability**: Track performance of microservices.
- **Infrastructure monitoring**: Monitor AWS and on-premises infrastructure.
- **Application performance monitoring**: Track application metrics.
- **Custom metrics**: Collect and analyze custom application metrics.
- **Alerting**: Detect and respond to anomalies and issues.
- **DevOps dashboards**: Create operational dashboards.
- **Capacity planning**: Analyze trends for resource optimization.
- **SLO tracking**: Monitor service level objectives.
- **Cross-team observability**: Share metrics across teams.

## Integration with AWS Services

- **[[Amazon Elastic Kubernetes Service (Amazon EKS)]]**: Native integration with Kubernetes metrics.
- **[[Amazon Elastic Container Service (Amazon ECS)]]**: Collect metrics from containerized applications.
- **[[AWS Lambda]]**: Monitor serverless applications.
- **[[Amazon EC2]]**: Monitor compute instances.
- **[[Amazon Managed Grafana]]**: Visualize Prometheus metrics.
- **[[Amazon CloudWatch]]**: Complement CloudWatch monitoring.
- **[[AWS Distro for OpenTelemetry]]**: Simplified metrics collection.
- **[[AWS PrivateLink]]**: Secure endpoint access.
- **[[AWS Identity and Access Management (IAM)]]**: Identity and access management.
- **[[AWS Organizations]]**: Cross-account management.

## Benefits

- **Operational simplicity**: No infrastructure to manage.
- **Cost-effective**: Pay only for metrics ingested and stored.
- **Scalability**: Automatically scales with your needs.
- **Compatibility**: Works with existing Prometheus tools and integrations.
- **Security**: Integrated with AWS security services.
- **High availability**: Replicated across multiple Availability Zones.
- **Long-term storage**: Retain metrics for extended periods.
- **Query performance**: Optimized for PromQL queries.
- **Seamless integration**: Native integration with AWS container services.
- **Ecosystem compatibility**: Works with the Prometheus ecosystem.

## Pricing

Amazon Managed Service for Prometheus pricing is based on:

- **Ingestion rate**: Cost per million samples ingested.
- **Storage**: Cost per GB of metric data stored.
- **Query sampling**: Cost per million samples queried.
- **Alerting and rules**: Cost per million samples evaluated.

There are no upfront commitments, and you only pay for what you use. Pricing varies by AWS region.