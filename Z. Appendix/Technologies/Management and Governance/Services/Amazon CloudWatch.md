---
group:
  - technology
---
Amazon CloudWatch is a monitoring and observability service that provides data and actionable insights for AWS, hybrid, and on-premises applications and infrastructure resources. CloudWatch collects and tracks metrics, collects and monitors log files, sets alarms, and automatically reacts to changes in your AWS resources.

## Key Components

### CloudWatch Metrics
- **Metrics collection**: Built-in and custom metrics from AWS and non-AWS resources.
- **Statistical functions**: Apply various functions (average, sum, minimum, maximum, etc.) to metrics.
- **Dimensions**: Filter metrics based on specific characteristics.
- **Resolution options**: Standard (1-minute) and high-resolution (1-second) metric granularity.
- **Metric math**: Create new metrics by performing calculations on existing metrics.
- **Metric streams**: Stream metrics to third-party service providers.
- **Anomaly detection**: Automatically identify abnormal metric patterns.
- **Metric insights**: SQL-like query language for metrics.

### CloudWatch Alarms
- **Threshold alarms**: Alert when metrics cross predefined thresholds.
- **Anomaly detection alarms**: Alert on unusual metric behavior.
- **Composite alarms**: Combine multiple alarms with logical operators.
- **Alarm actions**: Trigger automated responses when alarms change state.
- **State changes**: Track alarm state changes (OK, ALARM, INSUFFICIENT_DATA).
- **Alarm history**: Review historical alarm state changes.

### CloudWatch Logs
- **Log groups and streams**: Organize and manage log data.
- **Real-time processing**: Process logs as they arrive using subscription filters.
- **Log insights**: Interactive query and analysis of log data.
- **Contributor insights**: Identify top contributors to log events.
- **Log patterns**: Automatically detect and group similar log messages.
- **Log retention**: Configurable retention policies for log data.
- **Encryption**: Encrypt log data at rest.
- **Filtering and pattern matching**: Search logs based on specific patterns.
- **Export to S3**: Export log data to Amazon S3 for long-term storage.

### CloudWatch Dashboard
- **Custom dashboards**: Create personalized views of your metrics and alarms.
- **Cross-region dashboards**: View metrics from multiple AWS regions.
- **Cross-account dashboards**: View metrics from multiple AWS accounts.
- **Auto refresh**: Automatically refresh dashboard data.
- **Widget sharing**: Share specific dashboard widgets.
- **Dashboard sharing**: Share entire dashboards with others.
- **Live data**: View real-time data for your resources.

### CloudWatch Synthetics
- **Canary scripts**: Create scripts that monitor endpoints and APIs.
- **Blueprint canaries**: Pre-built monitoring templates.
- **Scheduled monitoring**: Run canaries on a regular schedule.
- **Screenshot capture**: Visual monitoring of web applications.
- **Artifact storage**: Store canary run artifacts in S3.
- **Integration with alarms**: Alert when canaries detect issues.

### CloudWatch RUM (Real-User Monitoring)
- **Client-side telemetry**: Collect performance data from real user sessions.
- **Page load times**: Monitor how quickly pages load for users.
- **Client-side errors**: Track JavaScript errors in the browser.
- **User journey tracking**: Understand how users navigate your application.
- **Geographic analytics**: View performance by user location.
- **Browser and device metrics**: Track performance across different environments.

### CloudWatch ServiceLens
- **Application health visualization**: View the health of your applications.
- **Trace integration**: Integrate with AWS X-Ray for distributed tracing.
- **Service map**: Visualize service dependencies and performance.
- **Correlation**: Connect traces, metrics, and logs for comprehensive debugging.

## Common Use Cases

- **Infrastructure monitoring**: Monitor performance and health of AWS resources.
- **Application monitoring**: Track application performance and errors.
- **Operational visibility**: Gain insights into operational health.
- **Troubleshooting**: Identify and resolve application and infrastructure issues.
- **Resource optimization**: Identify underutilized or overutilized resources.
- **Compliance auditing**: Track and record resource configuration changes.
- **Security monitoring**: Detect and respond to suspicious activity.
- **Automated remediation**: Automatically fix common issues.
- **SLA tracking**: Monitor service level agreement compliance.
- **Billing alerts**: Get notified when costs exceed thresholds.

## Integration with AWS Services

CloudWatch integrates with virtually all AWS services, including:
- **[[Amazon EC2]]**: Detailed monitoring for instances.
- **[[AWS Lambda]]**: Monitor function performance and errors.
- **[[Amazon RDS]]**: Database instance metrics and logs.
- **[[Amazon S3]]**: Bucket metrics and request tracking.
- **[[AWS Auto Scaling]]**: Trigger scaling based on CloudWatch metrics.
- **[[Amazon EventBridge]]**: Respond to CloudWatch events.
- **[[Amazon Simple Notification Service (Amazon SNS)]]**: Send notifications for alarm state changes.
- **[[AWS X-Ray]]**: Connected trace and metric visualization.
- **[[Amazon Elastic Container Service (Amazon ECS)]]**: Container insights for monitoring.
- **[[Amazon Elastic Kubernetes Service (Amazon EKS)]]**: Container insights for monitoring.
- **[[AWS CloudTrail]]**: Log and monitor API activity.

## Benefits

- **Unified monitoring**: Single platform for metrics, logs, and traces.
- **Full-stack visibility**: Monitor from infrastructure to application.
- **Actionable insights**: Detect issues before they impact users.
- **Automated response**: Take automated actions based on alarms.
- **Operational efficiency**: Reduce time to identify and resolve issues.
- **Cost optimization**: Identify resource optimization opportunities.
- **Scalability**: Monitors resources at any scale.
- **Cross-platform support**: Monitor AWS, hybrid, and on-premises resources.
- **Customizability**: Define custom metrics and dashboards.
- **Security and compliance**: Centralized logging for audit and compliance.

## Pricing

Amazon CloudWatch pricing is based on:
- **Metrics**: Number of metrics, API requests, and dashboards
- **Logs**: Data ingestion, storage, and analysis
- **Alarms**: Number of alarm metrics and API requests
- **Events**: Number of events and rule invocations
- **Synthetics**: Number of canary runs
- **RUM**: Number of user sessions monitored
- **Evidently**: Number of events recorded

Free tier allowances are available for new AWS customers for the first 12 months.