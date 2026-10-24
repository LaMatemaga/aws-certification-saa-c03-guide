---
group:
  - technology
---
Amazon Managed Grafana is a fully managed service that makes it easy to deploy, operate, and scale Grafana, a popular open-source analytics platform. With Amazon Managed Grafana, you can analyze your metrics, logs, and traces without having to manage the underlying infrastructure.

## Key Features

- **Fully managed service**: No need to provision servers, setup software, or perform upgrades.
- **Workspace architecture**: Create multiple isolated Grafana workspaces.
- **Enterprise plugins**: Access to enterprise plugins without additional licenses.
- **Data source integration**: Native integration with AWS and third-party data sources.
- **Cross-account data source access**: Query data across multiple AWS accounts.
- **High availability**: Built-in fault tolerance and high availability.
- **Automatic upgrades**: Regular updates with the latest Grafana versions.
- **Scalability**: Automatically scales to handle varying workloads.
- **AWS Identity integration**: Authentication via IAM, IAM Identity Center, or SAML.
- **Private VPC access**: Access your workspace via private VPC endpoints.
- **Network access controls**: Control network access to your workspaces.
- **Encryption**: Data encryption at rest and in transit.
- **Alerts and notifications**: Set up alerts and send notifications.
- **Dashboard as code**: Manage dashboards using the API or Terraform.
- **Audit logging**: Track user activity and changes to resources.

## Data Source Integrations

### AWS Data Sources

- **[[Amazon CloudWatch]]**: Metrics, logs, and alarms.
- **[[Amazon Managed Service for Prometheus]]**: High-cardinality metrics.
- **[[AWS X-Ray]]**: Distributed tracing data.
- **[[Amazon OpenSearch Service]]**: Log analytics and search.
- **[[Amazon Timestream]]**: Time series data.
- **[[Amazon Athena]]**: SQL queries on S3 data.
- **[[AWS IoT SiteWise]]**: Industrial equipment data.
- **[[Amazon Redshift]]**: Data warehouse analytics.
- **[[Amazon DynamoDB]]**: NoSQL database metrics.
- **[[AWS Lambda]]**: Serverless function metrics.

### Third-Party Data Sources

- **Prometheus**: Open-source metrics collection and querying.
- **Graphite**: Time-series metrics database.
- **InfluxDB**: Time-series database.
- **MySQL/PostgreSQL**: Relational databases.
- **Microsoft SQL Server**: Enterprise database metrics.
- **OpenTSDB**: Scalable time series database.
- **Elasticsearch**: Search and analytics engine.
- **Splunk**: Machine data platform.
- **Datadog**: Monitoring service for cloud applications.
- **New Relic**: Application performance monitoring.

## Visualization Types

- **Time-series graphs**: Visualize data over time.
- **Gauges and stat panels**: Display single-value metrics.
- **Bar charts and histograms**: Compare values across categories.
- **Heatmaps**: Show patterns in large datasets.
- **Tables**: Display data in tabular format.
- **Pie charts**: Show proportional relationships.
- **Logs panels**: View and search log entries.
- **Traces panels**: Visualize distributed traces.
- **Geomaps**: Visualize geospatial data.
- **State timeline**: Track state changes over time.
- **Node graphs**: Visualize network relationships.
- **Candlestick charts**: Display financial data.
- **Custom panels**: Create custom visualizations.

## Common Use Cases

- **Infrastructure monitoring**: Monitor performance of your AWS infrastructure.
- **Application performance monitoring**: Track application metrics and performance.
- **Container and microservices monitoring**: Monitor containerized applications.
- **IoT device monitoring**: Visualize data from IoT devices.
- **Business intelligence dashboards**: Create dashboards for business metrics.
- **Log analysis**: Search and visualize log data.
- **Distributed tracing**: Analyze application traces for performance bottlenecks.
- **Cloud cost monitoring**: Track AWS service costs and usage.
- **DevOps visibility**: Provide operational visibility to DevOps teams.
- **Cross-account monitoring**: Monitor resources across multiple AWS accounts.

## Integration with AWS Services

- **AWS Security Hub**: Visualize security findings.
- **AWS CloudTrail**: Monitor API activity and user actions.
- **Amazon EventBridge**: Respond to changes in your environment.
- **AWS IAM Identity Center**: Single sign-on for users.
- **AWS Organizations**: Deploy workspaces across your organization.
- **AWS Resource Access Manager**: Share resources across accounts.
- **AWS PrivateLink**: Secure access to your workspaces.
- **AWS Key Management Service**: Encrypt your workspace data.
- **AWS Global Accelerator**: Access workspaces from global locations.

## Benefits

- **Operational simplicity**: No infrastructure to manage or maintain.
- **Cost-effective**: Pay only for active users without upfront costs.
- **Enterprise ready**: Secure, highly available, and scalable.
- **Unified observability**: Single pane of glass for metrics, logs, and traces.
- **Flexible data source support**: Connect to AWS and third-party sources.
- **Comprehensive security**: Integrated with AWS security services.
- **Multi-account visibility**: Monitor resources across accounts.
- **Easy setup**: Deploy workspaces in minutes.
- **Automated updates**: Always run the latest Grafana version.
- **Developer friendly**: APIs for programmatic management.

## Pricing

Amazon Managed Grafana pricing is based on:

- **Active users**: Pay per active user (who logs in during the month).
- **Workspace tiers**: Different pricing tiers based on features and usage.

There are no upfront commitments, and you only pay for what you use. Additional charges may apply for data transfer and storage in the connected data sources.