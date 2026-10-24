---
group:
  - technology
---
Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. It acts as a "front door" for applications to access data, business logic, or functionality from your backend services, such as workloads running on Amazon EC2, code running on AWS Lambda, any web application, or real-time communication applications.

## Key Features

- **API types**: Support for RESTful APIs, WebSocket APIs, and HTTP APIs.
- **Endpoint types**: Regional, edge-optimized, and private endpoints.
- **Request throttling**: Control the rate of requests to your API.
- **Authorization**: Multiple options for controlling access to your APIs.
- **API keys and usage plans**: Track and limit usage by API key.
- **Caching**: Cache API responses to improve performance.
- **Request/response transformations**: Modify requests and responses on the fly.
- **OpenAPI specification support**: Import and export API definitions.
- **SDK generation**: Automatically generate client SDKs.
- **Custom domains**: Use your own domain names for APIs.
- **Canary deployments**: Gradually shift traffic to new API versions.
- **Monitoring and metrics**: Track API usage and performance.
- **Request validation**: Validate request parameters and body.
- **WAF integration**: Protect APIs from common web exploits.
- **Resource policies**: Control who can access your API.
- **Private integrations**: Connect to private VPC resources.

## API Types

### REST APIs

- **Resource-based modeling**: Create APIs using resource hierarchy.
- **Advanced features**: Full set of API Gateway features.
- **Integration options**: Connect to various backend services.
- **Powerful security controls**: Fine-grained access control options.
- **API management features**: Keys, usage plans, throttling.
- **Response transformations**: Modify and shape response data.

### HTTP APIs

- **Optimized for serverless workloads**: Streamlined for Lambda and HTTP backends.
- **Lower latency**: Up to 60% lower latency than REST APIs.
- **Lower cost**: More cost-effective than REST APIs.
- **Simplified routing**: CORS support and automatic deployments.
- **OpenID Connect and OAuth 2.0 authorization**: Built-in support.
- **JWT authorizers**: Validate JSON web tokens for authorization.

### WebSocket APIs

- **Persistent connections**: Maintain connections for real-time communication.
- **Bi-directional communication**: Both client and server can send messages.
- **Route message based on content**: Send messages to different backends based on content.
- **Connection management**: Manage and monitor active connections.
- **Serverless architecture**: Integrate with Lambda for serverless backends.
- **Automatic scaling**: Handle varying numbers of connections.

## Integration Types

- **Lambda function**: Invoke [[AWS Lambda]] functions.
- **HTTP endpoints**: Connect to HTTP/HTTPS endpoints.
- **AWS services**: Integrate directly with AWS services.
- **Mock integrations**: Return static responses without backend calls.
- **VPC link**: Connect to resources in a VPC.
- **Private integration**: Access private resources securely.
- **Step Functions**: Trigger Step Functions state machines.
- **Event Bridge**: Send events to [[Amazon EventBridge]].

## Common Use Cases

- **Serverless application backends**: Create backends for web, mobile, and IoT applications.
- **Microservices architecture**: Build and expose microservices.
- **SaaS integrations**: Create APIs for third-party access to your services.
- **Legacy system modernization**: Add modern APIs to existing systems.
- **Real-time applications**: Build chat, collaboration, and gaming applications.
- **Multi-tenant applications**: Manage access for different customer tiers.
- **Mobile backends**: Create scalable backends for mobile applications.
- **Internal service communication**: Standardize communication between services.
- **API monetization**: Create and monetize APIs as products.
- **Partner integrations**: Securely share capabilities with partners.
- **Public APIs**: Create and manage public-facing APIs.
- **Event-driven architectures**: Trigger events based on API calls.

## Security Features

- **IAM roles and policies**: Control who can access and manage APIs.
- **Lambda authorizers**: Create custom authorization logic.
- **Cognito User Pools**: User authentication and authorization.
- **OAuth/OpenID Connect**: Industry-standard authentication.
- **API keys**: Track and control usage by client.
- **Resource policies**: Restrict access based on source IP, VPC, or AWS account.
- **WAF integration**: Protect against common web exploits.
- **Private APIs**: Deploy APIs inside your VPC.
- **Client certificates**: Mutual TLS authentication.
- **AWS Shield integration**: DDoS protection.
- **Request throttling**: Protect backend services from traffic spikes.

## Monitoring and Management

- **CloudWatch integration**: Monitor API metrics and logs.
- **CloudWatch Logs**: Detailed logging of API requests and responses.
- **X-Ray integration**: Trace requests through your applications.
- **Usage dashboard**: View API usage and performance metrics.
- **Error reporting**: Track and analyze API errors.
- **Access logging**: Log who is accessing your APIs.
- **Execution logging**: Log the full request/response cycle.
- **API documentation**: Generate and host API documentation.
- **API versioning**: Manage multiple API versions.
- **Stage variables**: Configure different environments (dev, test, prod).

## Benefits

- **Scalability**: Handles any volume of API calls without provisioning infrastructure.
- **Performance**: Low latency for API requests with global reach.
- **Cost-effective**: Pay only for API calls received and data transferred.
- **Easy monitoring**: Built-in monitoring and metrics.
- **Flexible security controls**: Multiple options for authentication and authorization.
- **Developer productivity**: Focus on business logic rather than infrastructure.
- **Ecosystem integration**: Works seamlessly with AWS and third-party services.
- **Reliability**: Built on AWS's highly available infrastructure.
- **Reduced maintenance**: No servers to manage or update.
- **API lifecycle management**: Tools for the entire API lifecycle.

## Pricing

Amazon API Gateway pricing is based on:

- **API calls**: Number of API calls received.
- **Data transfer**: Amount of data transferred out.
- **Caching**: Optional API caching capacity.
- **WebSocket**: Connection minutes and messages for WebSocket APIs.

Different rates apply for REST APIs, HTTP APIs, and WebSocket APIs. A free tier is available for new users, including a certain number of API calls each month.