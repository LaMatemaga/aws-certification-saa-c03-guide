---
group:
  - technology
---
AWS Lambda is a serverless compute service that runs your code in response to events and automatically manages the underlying compute resources. With Lambda, you can run code without provisioning or managing servers, making it an ideal compute service for many application scenarios.

## Key Features

- **Serverless execution**: Run code without provisioning or managing servers.
- **Event-driven model**: Execute code in response to events from various AWS services.
- **Automatic scaling**: Lambda automatically scales your applications based on incoming request rates.
- **Stateless functions**: Design functions to be stateless for horizontal scaling.
- **Pay-per-use pricing**: Pay only for the compute time you consume.
- **Multiple language support**: Run code written in Node.js, Python, Java, Go, .NET, Ruby, and custom runtimes.
- **Function concurrency control**: Set reserved concurrency limits.
- **Execution duration**: Run functions for up to 15 minutes per execution.
- **Memory configuration**: Allocate from 128MB to 10GB of memory to your functions.
- **Layer support**: Package and share libraries across multiple functions.
- **Container image support**: Package and deploy Lambda functions as container images.
- **VPC connectivity**: Connect to resources in a private VPC.
- **Environment variables**: Configure function behavior without modifying code.
- **Versions and aliases**: Implement deployment strategies like blue/green and canary.

## Execution Models

- **Synchronous invocation**: Direct function calls that wait for a response.
- **Asynchronous invocation**: Events queued for processing with automatic retries.
- **Stream-based invocation**: Process records from streams like Kinesis or DynamoDB Streams.

## Event Sources

- **API Gateway**: Create RESTful or WebSocket APIs.
- **Application Load Balancer**: HTTP(S) request routing.
- **S3**: Object creation and deletion events.
- **DynamoDB**: Stream record processing.
- **Kinesis**: Stream processing.
- **SQS**: Message queue processing.
- **SNS**: Notification processing.
- **EventBridge**: Scheduled or event pattern triggers.
- **Step Functions**: Workflow orchestration.
- **CloudWatch Logs**: Log processing.
- **CodeCommit**: Repository event handling.
- **CloudFormation**: Custom resources.

## Common Use Cases

- **Web APIs**: Backend for web, mobile, and IoT applications.
- **Data processing**: Real-time file processing, stream processing, ETL operations.
- **Task automation**: Scheduled tasks, infrastructure management.
- **Event handling**: Processing event-driven workflows.
- **Backends for IoT**: Processing data from IoT devices.
- **Chatbots and voice assistants**: Backend logic for conversational interfaces.
- **Image and media processing**: On-the-fly transformation and analysis.
- **Machine learning inference**: Hosting ML models for prediction.

## Extensions

- **Lambda Extensions**: Custom monitoring, security, and governance tools.
- **Lambda Layers**: Reusable components for function code.
- **Lambda@Edge**: Run Lambda at AWS edge locations for content delivery.
- **Lambda Destinations**: Configure targets for asynchronous invocation results.

## Pricing

AWS Lambda pricing is based on:

- Number of requests
- Duration of execution (in milliseconds)
- Memory allocated to the function

There is a generous free tier that includes 1 million free requests per month and 400,000 GB-seconds of compute time.