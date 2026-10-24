---
group:
  - technology
---
Amazon Kendra is an intelligent search service powered by machine learning. It enables organizations to provide high-precision natural language search capabilities to their employees and customers across websites and applications. Unlike traditional search engines that rely on keyword matching, Kendra understands the context and intent behind queries to return more relevant results.

## Key Features

- **Natural language search**: Understand questions posed in natural language.
- **Semantic search**: Grasp the contextual meaning of queries beyond keywords.
- **Document ranking**: Use machine learning to rank documents by relevance.
- **Incremental learning**: Improve results over time based on user feedback.
- **FAQ matching**: Directly match questions to predefined answers.
- **Multi-language support**: Search in multiple languages.
- **Document filtering**: Filter results based on document attributes.
- **Custom synonyms**: Define business-specific synonyms to improve search relevance.
- **Custom tuning**: Boost or bury results based on specific attributes.
- **Faceted search**: Narrow down results using various document attributes.
- **Suggested answers**: Extract specific passages that answer the query.
- **Query suggestions**: Provide auto-complete suggestions as users type.
- **User context filtering**: Personalize search results based on user attributes.
- **Relevance feedback**: Incorporate user feedback to improve future searches.
- **Field-based search**: Target searches to specific document fields.

## Supported Data Sources

- **Amazon S3**: Document repositories stored in S3 buckets.
- **Microsoft SharePoint**: Connect to SharePoint Online and On-premises.
- **Microsoft OneDrive**: Access files stored in OneDrive.
- **Google Drive**: Index documents from Google Drive.
- **Salesforce**: Connect to Salesforce objects and Knowledge Articles.
- **ServiceNow**: Index ServiceNow knowledge bases.
- **Confluence**: Search across Confluence wikis.
- **Box**: Connect to Box document repositories.
- **Dropbox**: Index files stored in Dropbox.
- **Databases**: Connect to RDS databases via JDBC.
- **Web crawlers**: Index content from websites.
- **Custom data sources**: Build connectors for proprietary data stores.

## Document Types

- **HTML**: Web pages and HTML documents.
- **PDF**: Adobe PDF documents.
- **Microsoft Word**: .doc and .docx files.
- **Microsoft PowerPoint**: .ppt and .pptx files.
- **Microsoft Excel**: .xls and .xlsx files.
- **Plain text**: .txt files.
- **RTF**: Rich Text Format documents.
- **Markdown**: Formatted text documents.
- **FAQ documents**: Question and answer pairs.
- **Custom formats**: Support for other formats through custom data sources.

## Common Use Cases

- **Employee knowledge bases**: Help employees find internal documentation.
- **Customer support portals**: Enable customers to find answers quickly.
- **Research repositories**: Search across research papers and findings.
- **Legal document search**: Find specific clauses and precedents in legal documents.
- **Healthcare information**: Search medical records and research.
- **Educational content**: Search across learning materials and courses.
- **Product documentation**: Help users find relevant product information.
- **Financial research**: Search across financial reports and analysis.
- **IT support**: Find solutions to technical problems.
- **Compliance documentation**: Search through regulatory and compliance documents.

## Integration with AWS Services

- **[[Amazon S3]]**: Store and index documents from S3 buckets.
- **[[AWS Identity and Access Management (IAM)]]**: Control access to Kendra resources.
- **[[Amazon CloudWatch]]**: Monitor Kendra usage and performance.
- **[[AWS CloudTrail]]**: Track user activity and API usage.
- **[[AWS Lambda]]**: Process documents before indexing.
- **[[Amazon VPC]]**: Deploy Kendra in a private VPC.
- **[[Amazon Comprehend]]**: Extract entities and key phrases.
- **[[Amazon Textract]]**: Extract text from document images.
- **[[Amazon Translate]]**: Translate queries and documents.
- **[[Amazon Lex]]**: Integrate with conversational interfaces.

## Benefits

- **Improved search accuracy**: Higher precision than keyword-based search.
- **Natural language understanding**: Users can ask questions in their own words.
- **Reduced search time**: Find information faster with relevant results.
- **Consolidated search**: Search across multiple repositories.
- **Self-improving**: Learn and improve from user interactions.
- **Easy deployment**: Deploy without ML expertise.
- **Scalability**: Handle from thousands to millions of documents.
- **Security**: Secure access with document-level security.
- **Customization**: Tailor search to your specific domain.
- **Analytics**: Gain insights from search patterns and behaviors.

## Pricing

Amazon Kendra pricing is based on:

- **Edition tier**: Developer or Enterprise edition.
- **Index units**: Capacity units for document storage and queries.
- **Query volume**: Number of searches performed.
- **Connectors**: Usage of pre-built data source connectors.

The Enterprise Edition offers higher capacity, more connectors, and advanced features. Specific pricing varies by region, and a free tier is available for new users to explore capabilities.