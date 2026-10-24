---
group:
  - technology
---
Amazon Fraud Detector is a fully managed service that uses machine learning to identify potentially fraudulent activities. It automates the time-consuming and expensive steps needed to build, train, and deploy fraud detection models, making it easier for businesses to quickly identify suspicious online activities like payment fraud, fake account creation, and loyalty program abuse.

## Key Features

- **End-to-end fraud detection**: Complete solution from data ingestion to fraud scoring.
- **Custom fraud models**: Create models tailored to your specific business needs.
- **Domain-specific models**: Pre-built model types for common fraud use cases.
- **No ML expertise required**: Simplified interface for building fraud models.
- **Automated model training**: Automatically trains and optimizes fraud models.
- **Real-time fraud detection**: Score events in real-time via API calls.
- **Explainable results**: Understand why events were flagged as fraudulent.
- **Rule-based decisioning**: Create custom rules to augment model predictions.
- **Fraud model versioning**: Track and manage different versions of models.
- **Event monitoring**: Monitor and store event evaluation results.
- **Visualization tools**: Graphical interface to explore model performance.
- **Variable importance**: Identify which factors contribute most to fraud detection.
- **Fraud outcomes management**: Define actions to take based on fraud scores.
- **Amazon SageMaker integration**: Bring custom models from SageMaker.
- **Batch prediction**: Evaluate fraud for a batch of past events.

## Fraud Detection Process

1. **Data collection**: Gather historical data about legitimate and fraudulent events.
2. **Data preparation**: Format data for model training.
3. **Model training**: Automatically train fraud detection models.
4. **Model deployment**: Deploy models for real-time or batch prediction.
5. **Event evaluation**: Submit new events for fraud scoring.
6. **Decision logic**: Apply rules to determine actions based on fraud scores.
7. **Performance monitoring**: Track model effectiveness over time.
8. **Model retraining**: Update models with new data for continued accuracy.

## Model Types

- **Online Fraud Insights**: Designed for detecting online fraud like payment fraud.
- **Transaction Fraud Insights**: Optimized for payment transaction fraud.
- **Account Takeover Insights**: Specialized for detecting account takeover attempts.
- **Custom model**: Create models optimized for your specific fraud patterns.
- **External models**: Integrate models created in Amazon SageMaker.

## Common Use Cases

- **Payment fraud detection**: Identify fraudulent payment transactions.
- **Account registration abuse**: Detect fake account creation attempts.
- **Guest checkout fraud**: Identify suspicious guest checkout patterns.
- **Loyalty program abuse**: Prevent abuse of reward and loyalty programs.
- **Free trial and promotion abuse**: Detect multiple sign-ups for free offers.
- **Account takeover prevention**: Identify suspicious login and account activity.
- **Financial services fraud**: Detect fraudulent loan applications or claims.
- **Retail fraud**: Identify return fraud, coupon abuse, or other retail fraud.
- **Marketplace fraud**: Detect fraudulent listings or seller activities.
- **Healthcare fraud**: Identify suspicious claims or billing patterns.

## Integration with AWS Services

- **[[Amazon S3]]**: Store training data and batch prediction results.
- **[[AWS Identity and Access Management (IAM)]]**: Control access to Fraud Detector resources.
- **[[Amazon CloudWatch]]**: Monitor API calls and service metrics.
- **[[AWS CloudTrail]]**: Track user activity and API usage.
- **[[Amazon EventBridge]]**: Create event-driven workflows based on fraud detection.
- **[[AWS Lambda]]**: Automate responses to detected fraud.
- **[[Amazon SageMaker]]**: Bring custom ML models for fraud detection.
- **[[AWS Glue]]**: Process and transform data for fraud detection.
- **[[Amazon QuickSight]]**: Visualize fraud detection results and trends.
- **[[AWS Key Management Service (KMS)]]**: Encrypt sensitive fraud detection data.

## Benefits

- **Reduced development time**: Deploy fraud detection in days instead of months.
- **Accuracy**: Models built with Amazon's 20+ years of fraud detection experience.
- **Customization**: Models tailored to your specific business and fraud patterns.
- **Scalability**: Handle from hundreds to millions of events.
- **Cost-effectiveness**: Pay only for what you use with no upfront costs.
- **Ease of use**: No specialized ML expertise required.
- **Adaptability**: Models that learn and improve over time.
- **Transparency**: Understand why events were flagged as fraudulent.
- **Security**: Secure handling of sensitive data with encryption.
- **Integration**: Easy integration with existing applications and workflows.

## Pricing

Amazon Fraud Detector pricing is based on:

- **Model training**: Pay per hour for model training.
- **Event evaluations**: Pay per event evaluated for fraud.
- **Storage**: Pay for storing fraud detection resources.

Specific rates vary by region. Amazon offers a free tier for new users that includes a certain number of model training hours and event evaluations each month.