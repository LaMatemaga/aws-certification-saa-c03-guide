---
group:
  - technology
---
AWS Fargate is a serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS). Fargate eliminates the need to provision and manage servers, allowing you to focus on designing and building your applications instead of managing the infrastructure that runs them.

## Key Features

- **Serverless container execution**: Run containers without managing servers or clusters.
- **On-demand scaling**: Scale precisely with the needs of your application.
- **Pay-per-use pricing**: Pay only for the resources used to run your containers.
- **Isolation and security**: Each container runs in its own isolated environment.
- **Integration with AWS services**: Seamless integration with other AWS services like IAM, VPC, and CloudWatch.
- **Compatibility**: Works with both Amazon ECS and Amazon EKS.
- **Resource definition**: Specify CPU and memory requirements at the container level.
- **Task networking**: Each task gets its own elastic network interface and IP address.
- **Storage options**: Support for ephemeral storage and integration with EFS for persistent storage.

## Benefits

- **No infrastructure management**: Eliminate the operational overhead of managing EC2 instances.
- **Right-sized resources**: Specify and pay for resources at the container level.
- **Security by isolation**: Enhanced security with isolated compute environments.
- **Simplified workflow**: Focus on building and deploying applications rather than managing infrastructure.

## Common Use Cases

- **Microservices architecture**: Deploy containerized microservices without managing infrastructure.
- **Batch processing**: Run batch jobs without worrying about underlying compute resources.
- **Web applications**: Host web applications with automated scaling based on demand.
- **API backends**: Run containerized API services.
- **Machine learning deployment**: Deploy machine learning models in containers.
- **Event-driven processing**: Process events using containerized applications.
- **Application modernization**: Move from monoliths to containers without managing infrastructure.

## Integrations

- **Amazon ECS**: Native integration for running containers without managing servers.
- **Amazon EKS**: Run Kubernetes pods without nodes to manage.
- **AWS IAM**: Fine-grained access controls for your Fargate tasks.
- **Amazon VPC**: Network controls and security for your containers.
- **AWS CloudWatch**: Monitor and log Fargate tasks.
- **AWS Load Balancer**: Distribute traffic to your Fargate tasks.
- **Amazon EFS**: Persistent storage for your containers.
- **AWS App Mesh**: Service mesh for microservices architecture.

## Pricing

AWS Fargate pricing is based on the vCPU and memory resources used from the time you start to download your container image until the task terminates, rounded up to the nearest second. There are no upfront commitments required, and you only pay for what you use.