---
group:
  - technology
---
Amazon Neptune is a fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets. The core of Neptune is a purpose-built, high-performance graph database engine optimized for storing billions of relationships and querying the graph with milliseconds latency.

## Key Features

- **Fully managed service**: AWS handles administration, maintenance, and patching.
- **Purpose-built graph engine**: Optimized for graph workloads.
- **Multiple graph models**: Support for both Property Graph and RDF/SPARQL.
- **High performance**: Optimized for highly connected data queries.
- **High availability**: Replicated across multiple Availability Zones.
- **Fault tolerance**: Data is durably stored with 6 copies across 3 AZs.
- **Read scaling**: Up to 15 read replicas for high read throughput.
- **Continuous backup**: Point-in-time recovery for up to 35 days.
- **Encryption**: Data encrypted at rest and in transit.
- **VPC security**: Run within an Amazon VPC for network isolation.
- **Audit logging**: Integration with CloudTrail for API tracking.
- **Open standards**: Support for popular graph query languages.
- **ML integration**: Built-in machine learning capabilities.
- **Data loading utilities**: Bulk data loading from S3.
- **Visualization**: Graph visualization through Neptune Workbench.
- **Serverless option**: Automatically scale capacity with Neptune Serverless.
- **Global database option**: Cross-region replication for global deployments.

## Graph Models and Query Languages

- **Property Graph Model**:
    
    - Vertices (nodes) with properties
    - Edges (relationships) with properties and direction
    - **Gremlin**: Apache TinkerPop Gremlin traversal language
    - **openCypher**: Declarative pattern-matching query language
- **RDF Graph Model** (Resource Description Framework):
    
    - Triples (subject-predicate-object)
    - W3C standard for semantic web
    - **SPARQL**: SQL-like query language for RDF data

## Instance Types and Deployment Options

- **Instance classes**: Various instance types optimized for different workloads:
    - **Memory optimized (r-classes)**: For memory-intensive applications.
    - **Burstable (t-classes)**: For development and test environments.
- **Deployment options**:
    - **Provisioned**: Traditional instances with fixed capacity.
    - **Serverless**: Auto-scaling based on workload needs.
    - **Global database**: Clusters spanning multiple regions.
    - **Multi-AZ**: High availability across availability zones.

## Graph Analytics and Machine Learning

- **Neptune Analytics**: Graph analytics at scale with billion-edge graphs.
- **Built-in algorithms**: PageRank, shortest path, connected components, etc.
- **Neptune ML**: Machine learning on graph data.
- **Graph embedding**: Learn vector representations of nodes and edges.
- **Node classification**: Predict node properties and labels.
- **Link prediction**: Predict relationships between nodes.
- **Integration with SageMaker**: Leverage Amazon SageMaker's ML capabilities.
- **Python integration**: Use Python for graph analytics.

## Common Use Cases

- **Knowledge graphs**: Organize and query complex information networks.
- **Identity graphs**: Connect and unify customer data across sources.
- **Fraud detection**: Identify suspicious patterns in transactions.
- **Social networking**: Build applications modeling social relationships.
- **Recommendation engines**: Generate personalized recommendations.
- **Network and IT operations**: Map infrastructure dependencies.
- **Life sciences research**: Model protein interactions and drug discovery.
- **Security investigation**: Track security threats and incidents.
- **Metadata management**: Track relationships between data assets.
- **Supply chain management**: Model complex supplier networks.
- **Regulatory compliance**: Track data lineage and governance.
- **Academic research**: Model complex relationships in research data.
- **Semantic web applications**: Build applications using RDF and SPARQL.
- **Bill of materials**: Track product components and relationships.

## Integration with AWS Services

- **[[Amazon EC2]]**: Host applications that access Neptune.
- **[[Amazon VPC]]**: Network isolation and security.
- **[[AWS Identity and Access Management (IAM)]]**: Authentication and authorization.
- **[[Amazon S3]]**: Store and load data from S3 buckets.
- **[[Amazon CloudWatch]]**: Monitor database performance.
- **[[AWS CloudTrail]]**: Track API calls and user activity.
- **[[AWS Lambda]]**: Serverless functions to interact with Neptune.
- **[[Amazon SageMaker]]**: Advanced machine learning with graph data.
- **[[AWS Glue]]**: ETL jobs to prepare data for Neptune.
- **[[Amazon Comprehend]]**: Extract entities for knowledge graphs.
- **[[Amazon QuickSight]]**: Visualize query results.
- **[[AWS Backup]]**: Centralized backup management.

## Benefits

- **Purpose-built for graphs**: Optimized for graph queries and traversals.
- **High performance**: Fast queries on highly connected data.
- **Scalability**: Scale to billions of relationships.
- **High availability**: 99.99% availability with multi-AZ deployments.
- **Security**: Comprehensive security features.
- **Standard APIs**: Use popular graph query languages.
- **Simplified operations**: Fully managed with automatic upgrades.
- **Flexibility**: Support for multiple graph models.
- **Cost-effective**: Pay only for resources used.
- **Integrated ML**: Built-in machine learning capabilities.
- **Developer friendly**: Multiple language bindings and examples.

## Pricing

Amazon Neptune pricing is based on:

- **Instance hours**: Hourly rate dependent on instance class.
- **Storage usage**: Pay per GB-month of storage used.
- **I/O operations**: Pay per million I/O requests.
- **Backup storage**: Charges for backup storage beyond the database size.
- **Data transfer**: Standard AWS data transfer rates apply.
- **Serverless consumption**: Pay per Neptune Capacity Unit (NCU) hour when using Serverless.

Neptune offers reserved instances for cost savings on long-term commitments. Pricing varies by region and deployment option.