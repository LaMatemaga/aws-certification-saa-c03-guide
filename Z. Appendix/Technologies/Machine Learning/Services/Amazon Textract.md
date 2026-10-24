---
group:
  - technology
---
Amazon Textract is a service that automatically extracts text, handwriting, and data from scanned documents. It goes beyond simple optical character recognition (OCR) to identify, understand, and extract data from forms and tables. With Textract, you can quickly automate document processing workflows, allowing you to process millions of document pages in hours.

## Key Features

- **Text extraction**: Extract printed text and handwriting from documents.
- **Form extraction**: Identify form fields and extract their values.
- **Table extraction**: Extract data presented in tables, maintaining row and column relationships.
- **Key-value pair extraction**: Identify key-value pairs in documents.
- **Document structure understanding**: Recognize document structure and relationships.
- **Checkboxes detection**: Identify and determine the state of checkboxes.
- **Query-based extraction**: Extract specific data using natural language queries.
- **Expense extraction**: Identify and extract information from receipts and invoices.
- **Identity document extraction**: Extract information from identity documents.
- **Lending document extraction**: Specialized extraction for mortgage and lending documents.
- **Handwriting recognition**: Process both printed text and handwriting.
- **Automatic language detection**: Process mixed-language documents.
- **Document analysis**: Understand document layout and structure.
- **Confidence scores**: Provide confidence levels for extracted text and relationships.

## Document Types Supported

- **Plain documents**: Letters, articles, and reports.
- **Forms**: Application forms, questionnaires, and structured documents.
- **Tables**: Financial statements, spreadsheets, and data tables.
- **Receipts**: Expense receipts for purchases and services.
- **Invoices**: Business invoices and bills.
- **Identity documents**: Driver's licenses, passports, identity cards.
- **Financial documents**: Bank statements, tax forms, financial reports.
- **Healthcare documents**: Medical forms, insurance claims, prescriptions.
- **Legal documents**: Contracts, agreements, and legal forms.
- **Handwritten notes**: Written text and annotations.
- **Mixed documents**: Documents containing text, forms, and tables.
- **Low-resolution documents**: Documents with varying quality levels.
- **Mortgage documents**: Loan applications, closing disclosures, etc.
- **Pay stubs**: Employment income verification documents.

## Processing Methods

- **Synchronous processing**: Real-time processing for single-page documents.
- **Asynchronous processing**: Process multi-page documents and large batches.
- **Batch processing**: Process large document collections.
- **Human review workflows**: Integrate human verification for uncertain extractions.
- **Custom extraction**: Train custom extractors for specific document types.
- **Query-based extraction**: Extract specific data points using natural language queries.

## Common Use Cases

- **Automated data entry**: Extract data from forms without manual entry.
- **Document digitization**: Convert physical documents to searchable digital formats.
- **Invoice processing**: Automate accounts payable workflows.
- **Expense management**: Extract data from receipts for expense reports.
- **Mortgage processing**: Streamline mortgage application processing.
- **Insurance claims processing**: Extract information from claim forms.
- **Healthcare form processing**: Digitize patient forms and medical records.
- **Legal document analysis**: Extract key information from legal documents.
- **Financial document processing**: Extract data from financial statements.
- **Identity verification**: Extract and verify information from ID documents.
- **Tax form processing**: Automate tax form data extraction.
- **Contract analysis**: Extract key terms and conditions from contracts.
- **HR document processing**: Process employment and onboarding documents.
- **Mail room automation**: Sort and route incoming correspondence.

## Integration with AWS Services

- **[[Amazon S3]]**: Store documents and extraction results.
- **[[AWS Lambda]]**: Process documents based on events.
- **[[Amazon A2I]]**: Human review of low-confidence extractions.
- **[[Amazon Comprehend]]**: Analyze extracted text for insights.
- **[[AWS Step Functions]]**: Orchestrate document processing workflows.
- **[[Amazon DynamoDB]]**: Store extracted data.
- **[[Amazon Simple Notification Service (Amazon SNS)]]**: Notifications for completed extractions.
- **[[Amazon Simple Queue Service (Amazon SQS)]]**: Queue documents for processing.
- **[[AWS CloudTrail]]**: Audit Textract API calls.
- **[[Amazon CloudWatch]]**: Monitor extraction performance.
- **[[Amazon Kendra]]**: Make extracted text searchable.
- **[[Amazon Rekognition]]**: Complementary image analysis capabilities.

## Benefits

- **Accuracy**: High-quality extraction with minimal errors.
- **Automation**: Eliminate manual data entry and processing.
- **Scalability**: Process from a few to millions of documents.
- **Cost-effectiveness**: Reduce document processing costs.
- **Speed**: Process documents in seconds instead of hours.
- **Structure preservation**: Maintain document layout and relationships.
- **Integration**: Easy integration with existing workflows.
- **Managed service**: No infrastructure to set up or manage.
- **Continuous improvement**: Models regularly updated for better accuracy.
- **Security**: Secure document processing with encryption.

## Pricing

Amazon Textract pricing is based on:

- **Document pages processed**: Pay per page for each feature used.
- **Feature usage**: Different rates for text extraction, form extraction, table extraction, etc.
- **Processing type**: Synchronous or asynchronous processing.
- **Query-based extraction**: Additional charges for natural language queries.

Specific rates vary by region and feature. A free tier is available for new users that includes a certain number of pages each month.