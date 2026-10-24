---
group:
  - technology
---
AWS X-Ray is a service that collects data about requests that your application serves, and provides tools you can use to view, filter, and gain insights into that data to identify issues and opportunities for optimization. For any traced request to your application, you can see detailed information not only about the request and response, but also about calls that your application makes to downstream AWS resources, microservices, databases, and web APIs.

## Key Features

- **Distributed tracing**: Track requests as they travel through your application.
- **Service map**: Visualize connections between services and resources.
- **Trace analysis**: Identify performance bottlenecks and errors.
- **End-to-end visibility**: Follow requests from client to storage and back.
- **Latency distributions**: View performance patterns across your application.
- **Annotations and metadata**: Add custom data to traces for deeper insights.
- **Sampling rules**: Configure which requests to trace and at what rates.
- **Filter expressions**: Query and analyze specific trace data.
- **Error tracking**: Identify and troubleshoot errors in your application.
- **Performance monitoring**: Track and analyze application performance.
- **Custom subsegments**: Create custom spans to track internal operations.
- **Integrated insights**: Pre-built insights for common issues.
- **Trace groups**: Organize traces by URLs, users, or other criteria.
- **Service-level statistics**: Understand performance across services.
- **Encryption**: Encrypt data at rest and in transit.

## Components

- **X-Ray SDK**: Instruments your code to send trace data.
- **X-Ray daemon**: Collects and buffers trace data before sending to X-Ray service.
- **X-Ray API**: Programs interact with X-Ray through API calls.
- **X-Ray console**: Web interface for analyzing and visualizing trace data.
- **Service map**: Visualization of service connections and health.
- **Trace view**: Detailed view of individual request traces.
- **Analytics**: Tools for analyzing trace data.
- **Sampling rules**: Controls which requests get traced.
- **Groups**: Collection of traces that match specific criteria.
- **Insights**: Automated analysis of trace data.

## Supported Platforms and Languages

- **Languages**:
    
    - Java
    - Node.js
    - .NET
    - Go
    - Python
    - Ruby
    - PHP
- **Platforms**:
    
    - AWS Lambda
    - Amazon EC2
    - Amazon ECS
    - Amazon EKS
    - AWS Elastic Beanstalk
    - AWS App Runner
    - On-premises servers

## Common Use Cases

- **Microservice debugging**: Troubleshoot issues across distributed services.
- **Performance optimization**: Identify and fix performance bottlenecks.
- **Error detection**: Find and resolve errors in your application.
- **Dependency analysis**: Understand dependencies between services.
- **Service health monitoring**: Monitor the health of your services.
- **SLA compliance**: Ensure your application meets service level agreements.
- **Root cause analysis**: Identify the root cause of application issues.
- **User experience analysis**: Understand the performance users experience.
- **Database query optimization**: Identify slow database queries.
- **API integration debugging**: Troubleshoot issues with third-party APIs.
- **Cold start analysis**: Analyze Lambda function cold starts.
- **HTTP request tracing**: Track HTTP requests through your application.
- **Service-to-service communication**: Analyze communication between services.
- **Resource utilization**: Understand how your application uses AWS resources.

## Integration with AWS Services

X-Ray integrates with many AWS services, including:

- **[[AWS Lambda]]**: Trace serverless applications.
- **[[Amazon API Gateway]]**: Trace API requests.
- **[[AWS App Runner]]**: Trace containerized applications.
- **[[AWS App Mesh]]**: Trace service mesh communications.
- **[[Amazon Simple Notification Service (Amazon SNS)]]**: Trace message publishing.
- **[[Amazon Simple Queue Service (Amazon SQS)]]**: Trace message processing.
- **[[AWS Step Functions]]**: Trace workflow execution.
- **[[Amazon EventBridge]]**: Trace event processing.
- **[[Amazon EC2]]**: Trace applications running on EC2.
- **[[Amazon Elastic Container Service (Amazon ECS)]]**: Trace containerized applications.
- **[[Amazon Elastic Kubernetes Service (Amazon EKS)]]**: Trace Kubernetes applications.
- **[[AWS Elastic Beanstalk]]**: Trace web applications.
- **[[Amazon RDS]]**: Trace database queries.
- **[[Amazon DynamoDB]]**: Trace database operations.
- **[[AWS SDK clients]]**: Trace AWS API calls.

## Benefits

- **Improved troubleshooting**: Quickly identify and fix issues.
- **Enhanced performance**: Find and address performance bottlenecks.
- **Better visibility**: End-to-end view of request flow.
- **Reduced MTTR**: Decrease mean time to resolution for issues.
- **Proactive optimization**: Identify issues before they impact users.
- **Cross-service insights**: Understand interactions between services.
- **Development-production parity**: Use in all environments.
- **Minimal overhead**: Low impact on application performance.
- **Custom analysis**: Add business-specific data to traces.
- **Scalable monitoring**: Works from single server to large distributed systems.
- **DevOps enablement**: Facilitate collaboration between development and operations.

## Pricing

AWS X-Ray pricing is based on:

- **Trace collection**: Pay per million traces recorded.
- **Trace scanning**: Pay per million traces retrieved for analysis.
- **Trace storage**: First 30 days of storage included; additional retention at extra cost.

There is a free tier that provides a certain amount of traces each month at no charge. Pricing varies by region, and there are no upfront commitments or minimum fees.