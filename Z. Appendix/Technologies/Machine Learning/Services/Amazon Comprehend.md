---
group:
  - technology
---
Amazon Comprehend is a natural language processing (NLP) service that uses machine learning to find insights and relationships in text. It identifies the language of the text; extracts key phrases, places, people, brands, or events; understands how positive or negative the text is; analyzes text using tokenization and parts of speech; and automatically organizes a collection of text files by topic.

## Key Features

- **Language detection**: Identify the dominant language in text from over 100 languages.
- **Entity recognition**: Extract entities such as people, places, organizations, quantities, and dates.
- **Key phrase extraction**: Identify the main points in text.
- **Sentiment analysis**: Determine the emotional tone of text (positive, negative, neutral, or mixed).
- **Syntax analysis**: Analyze text using tokenization and parts of speech.
- **Topic modeling**: Organize text documents into topic categories.
- **Custom entity recognition**: Train custom models to recognize entities specific to your domain.
- **Custom classification**: Create custom text classification models for your specific needs.
- **PII detection and redaction**: Identify personally identifiable information in documents.
- **Document insights**: Extract key insights from unstructured documents.
- **Real-time analysis**: Process text in real-time via API calls.
- **Async batch processing**: Process large volumes of documents asynchronously.
- **Multi-language support**: Process text in English, Spanish, French, German, Italian, Portuguese, Arabic, Hindi, Japanese, Korean, Chinese, and more.
- **Medical domain insights**: Specific features for healthcare and life sciences (Comprehend Medical).

## How It Works

1. **Input**: Provide text data through the Comprehend API, console, or batch job.
2. **Processing**: Comprehend applies various NLP models to analyze the text.
3. **Output**: Receive structured data with extracted insights.
4. **Custom models**: Optionally train custom models using your labeled data.
5. **Deployment**: Use insights in applications, analytics, or downstream processes.

## Common Use Cases

- **Content personalization**: Analyze user-generated content to deliver personalized experiences.
- **Social media monitoring**: Extract insights from social media feeds.
- **Voice of customer analytics**: Understand customer feedback, reviews, and survey responses.
- **Content recommendation**: Categorize content to improve recommendation systems.
- **Search enhancement**: Improve search relevance using extracted entities and key phrases.
- **Compliance monitoring**: Detect sensitive information in documents.
- **News analysis**: Categorize and extract insights from news articles.
- **Document processing**: Automate document workflows by extracting relevant information.
- **Knowledge discovery**: Extract relationships and insights from large text collections.
- **Medical text analysis**: Extract medical conditions, medications, and procedures from clinical text.

## Integration with AWS Services

- **[[Amazon S3]]**: Process documents stored in S3 buckets.
- **[[Amazon Translate]]**: Combine with translation services for multilingual analysis.
- **[[AWS Lambda]]**: Trigger analysis functions in response to events.
- **[[Amazon Athena]]**: Query insights stored in S3 using SQL.
- **[[Amazon QuickSight]]**: Visualize extracted insights.
- **[[Amazon SageMaker]]**: Use extracted features in ML models.
- **[[AWS Glue]]**: Process and transform extracted data.
- **[[Amazon Kendra]]**: Improve search capabilities with extracted entities.
- **[[Amazon Textract]]**: Combine with document extraction for end-to-end document processing.
- **[[AWS Data Exchange]]**: Share insights with partners.

## Benefits

- **Reduced development time**: Use pre-trained models without ML expertise.
- **Scalability**: Process from a few documents to millions.
- **Accuracy**: High-quality models trained on diverse datasets.
- **Customization**: Train custom models for specific domains.
- **Cost-effectiveness**: Pay only for what you analyze.
- **Easy integration**: Simple APIs for integration with applications.
- **Continuous learning**: Models are regularly improved by AWS.
- **Managed infrastructure**: No servers to manage or maintain.
- **Security**: Secure processing with encryption and IAM integration.
- **Compliance**: Helps meet compliance requirements with PII detection.

## Pricing

Amazon Comprehend pricing is based on:

- **Real-time analysis**: Pay per unit of text processed (per 100 characters).
- **Batch processing**: Pay per unit of text processed in batch jobs.
- **Custom model training**: Pay for compute time used during training.
- **Custom model hosting**: Pay hourly fee for deployed custom models.
- **Document insights**: Pay per page for document processing.

Specific rates vary by region and feature. A free tier is available for new users to explore the service capabilities.