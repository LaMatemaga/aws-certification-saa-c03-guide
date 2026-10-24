---
group:
  - technology
---
Amazon Quantum Ledger Database (QLDB) is a fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log. QLDB tracks every application data change and maintains a complete and verifiable history of changes over time. It is purpose-built for applications that need to maintain a complete and accurate record of all changes to application data.

## Key Features

- **Immutable journal**: Append-only journal that tracks all changes.
- **Cryptographic verification**: Data integrity verification with SHA-256 hashing.
- **Document data model**: Flexible document-oriented storage.
- **SQL-like query language**: PartiQL for familiar, SQL-compatible queries.
- **ACID transactions**: Fully ACID compliant with serializable isolation.
- **Serverless**: Automatically scales to support application workloads.
- **Fully managed**: AWS handles administration, patching, and scaling.
- **Built-in history**: Time-travel queries to access historical data.
- **Streaming**: Journal changes can be streamed to other services.
- **Open data format**: Export data in standard formats.
- **Performance**: Low-latency reads and writes.
- **Data verification**: Cryptographic verification of data integrity.
- **Encryption**: Data encrypted at rest and in transit.
- **Streamlined development**: Driver libraries for multiple languages.
- **Pay-per-use pricing**: Pay only for storage and I/O consumed.

## Core Concepts

- **Journal**: The immutable transaction log that records all changes.
- **Ledger**: Top-level resource containing tables, journal, and indexed history.
- **Tables**: Collections of documents (similar to traditional database tables).
- **Documents**: JSON-like data objects.
- **Blocks**: Sequenced journal entries that contain document revisions.
- **Revisions**: Versions of documents at specific points in time.
- **Digest**: A cryptographic hash representing the entire journal.
- **Verification**: The process of proving data integrity using cryptographic techniques.
- **Streams**: Change data capture for integration with other systems.
- **PartiQL**: SQL-compatible query language for QLDB.

## Data Model

- **Document-oriented**: Flexible schema for JSON-like documents.
- **Revision model**: Each change creates a new document revision.
- **Ion document format**: Amazon Ion data format (superset of JSON).
- **User-defined indexes**: Create indexes to optimize query performance.
- **Table organization**: Organize documents into tables.
- **Metadata tracking**: Automatically tracked system metadata.
- **Optimistic concurrency control**: Manage concurrent updates.

## Query Capabilities

- **PartiQL language**: SQL-compatible query language.
- **CRUD operations**: Create, read, update, and delete operations.
- **Historical queries**: Query data at a specific point in time.
- **Document search**: Search document contents.
- **Aggregation**: Compute sums, averages, and other aggregates.
- **Joins**: Combine data from multiple tables.
- **Redaction**: Permanently remove document fields.
- **Bulk operations**: Execute operations on multiple documents.
- **Transactions**: Group multiple operations in a transaction.
- **Indexes**: Create and use indexes for query performance.

## Common Use Cases

- **Financial ledger systems**: Track financial transactions.
- **Supply chain traceability**: Record movement of goods.
- **Manufacturing process tracking**: Document manufacturing history.
- **Insurance claim history**: Maintain complete history of claims.
- **Healthcare records**: Track patient treatments and history.
- **Regulatory compliance**: Maintain auditable history for compliance.
- **System of record**: Serve as a verifiable system of record.
- **Digital registries**: Implement registries for assets or entities.
- **Legal documentation**: Store and verify legal documents.
- **Audit trails**: Maintain tamper-proof audit records.
- **Asset tracking**: Track ownership and transfers of assets.
- **Electronic health records**: Store complete patient history.
- **Record management**: Maintain official records with verification.
- **Public sector records**: Government records requiring verification.

## Integration with AWS Services

- **[[AWS Lambda]]**: Process QLDB data and events.
- **[[Amazon Kinesis]]**: Stream journal blocks for real-time processing.
- **[[Amazon S3]]**: Export data for long-term storage.
- **[[AWS Glue]]**: ETL for data integration.
- **[[Amazon Athena]]**: Query exported QLDB data using SQL.
- **[[Amazon CloudWatch]]**: Monitor QLDB performance metrics.
- **[[AWS CloudTrail]]**: Track API calls and user activity.
- **[[AWS Identity and Access Management (IAM)]]**: Authentication and authorization.
- **[[AWS Backup]]**: Centralized backup management.
- **[[AWS CloudFormation]]**: Infrastructure as code deployment.
- **[[Amazon EventBridge]]**: Respond to QLDB events.

## Benefits

- **Data integrity**: Cryptographic verification of data history.
- **Transparency**: Complete and accessible history of all data changes.
- **Performance**: High performance for transactional workloads.
- **Simplicity**: Familiar SQL-like query language.
- **Scalability**: Automatic scaling without provisioning.
- **Managed service**: No infrastructure to manage.
- **Time travel**: Easy access to historical data.
- **Compliance**: Helps meet regulatory requirements.
- **Cost-effective**: Pay only for what you use.
- **Developer friendly**: Multiple language SDKs.
- **Operational simplicity**: No need to build custom audit capabilities.

## Differences from Blockchain

- **Centralized**: Controlled by a single trusted authority (AWS).
- **Performance**: Higher transaction throughput than blockchain.
- **No consensus mechanism**: No need for distributed consensus.
- **Simplicity**: Easier to use than blockchain frameworks.
- **Managed service**: No distributed network to maintain.
- **Query capabilities**: SQL-like query language for data access.
- **Cost-effective**: Lower cost than running a blockchain network.

## Pricing

Amazon QLDB pricing is based on:

- **Storage**: Pay per GB-month of data stored.
- **Read I/O requests**: Pay per million read I/O requests.
- **Write I/O requests**: Pay per million write I/O requests.
- **Journal storage**: Pay per GB-month of journal storage.
- **Data transfer**: Standard AWS data transfer rates apply.
- **Stream requests**: Pay per million stream requests.

QLDB has no minimum fees or upfront costs. You pay only for what you use, with a free tier for new customers.