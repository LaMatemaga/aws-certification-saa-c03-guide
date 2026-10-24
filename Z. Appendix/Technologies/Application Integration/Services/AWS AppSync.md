---
group:
  - technology
---
AWS AppSync is a fully managed service that makes it easy to develop GraphQL APIs by handling the heavy lifting of securely connecting to data sources like AWS DynamoDB, Lambda, and more. AppSync enables real-time data syncing and offline programming capabilities for mobile and web applications.

## Key Features

- **GraphQL API development**: Create and run GraphQL APIs with minimal configuration.
- **Real-time data synchronization**: Automatically update connected clients and devices when data changes.
- **Offline capabilities**: Support for offline access and automatic conflict resolution.
- **Security**: Fine-grained authorization controls using API keys, IAM, OpenID Connect, and Amazon Cognito user pools.
- **Schema development**: Use GraphQL schema definition language (SDL) to define your API.
- **Resolver mapping**: Connect GraphQL operations to backend data sources with mapping templates.
- **Conflict detection and resolution**: Built-in conflict resolution strategies for multi-user applications.
- **Monitoring and logging**: Integration with AWS CloudWatch for monitoring and logging.

## Data Source Integrations

- Amazon DynamoDB
- AWS Lambda
- Amazon OpenSearch Service
- Aurora Serverless
- HTTP APIs
- Event Bridge
- Local resolvers (for static data)

## Common Use Cases

- **Mobile and web applications**: Build robust APIs for modern applications.
- **Real-time collaborative applications**: Enable concurrent updates with conflict resolution.
- **Offline-first applications**: Support for apps that work without continuous connectivity.
- **Chat applications**: Real-time messaging and updates.
- **IoT applications**: Data synchronization for Internet of Things applications.
- **Microservice aggregation**: Combine multiple microservices under a single GraphQL endpoint.
- **Content management systems**: APIs for content delivery and management.

## Client SDK Support

- Android
- iOS
- JavaScript
- React Native
- Flutter

## Pricing

AWS AppSync pricing is based on:

- API request count
- Real-time updates
- Data transfer out

There are no minimum fees or upfront commitments, and you only pay for what you use.