---
group:
  - technology
---
Amazon Forecast is a fully managed service that uses machine learning to deliver highly accurate time-series forecasts. Based on the same technology used at Amazon.com, Amazon Forecast enables you to achieve forecasting results that were previously only accessible to organizations with substantial resources to develop custom prediction models.

## Key Features

- **AutoML capability**: Automatically tests multiple algorithms to select the best-performing model.
- **Built-in algorithms**: Includes statistical and machine learning algorithms like ARIMA, ETS, DeepAR+, CNN-QR, Prophet, and NPTS.
- **Custom algorithms**: Support for bringing your own custom algorithms.
- **Accuracy evaluation**: Built-in forecast accuracy metrics (RMSE, MAPE, wQL, etc.).
- **Automatic retraining**: Automatically retrain models as new data becomes available.
- **Automatic preprocessing**: Handles missing values, outliers, and feature engineering.
- **Hierarchical forecasting**: Generate forecasts at different granularity levels.
- **Predictor explainability**: Understand which factors influence your forecasts.
- **What-if analysis**: Test hypothetical scenarios to understand potential outcomes.
- **Forecast exports**: Export forecasts to S3 for integration with other systems.
- **Handling cold starts**: Forecast for new items with limited or no history.
- **Related time-series**: Incorporate external variables that might affect forecasts.
- **Built-in holidays and events**: Automatically account for holidays and seasonal events.
- **Quantile forecasts**: Generate predictions at different probability levels.

## Data Integration

- **Input data types**:
    
    - **Target time-series**: The values you want to forecast.
    - **Related time-series**: External factors that might influence your target.
    - **Item metadata**: Additional information about the items being forecasted.
- **Data sources**:
    
    - **Amazon S3**: Import data directly from S3 buckets.
    - **CSV or Parquet format**: Support for standard data formats.
    - **Direct API input**: Programmatically provide data via API calls.
    - **AWS Data Exchange**: Access third-party data sets.
    - **AWS Glue**: Process and transform data before forecasting.

## Common Use Cases

- **Retail demand planning**: Forecast product demand for inventory management.
- **Supply chain optimization**: Plan resource allocation and logistics.
- **Workforce planning**: Predict staffing needs across locations and departments.
- **Financial planning**: Forecast revenue, cash flow, and other financial metrics.
- **Healthcare resource planning**: Predict patient admissions and resource needs.
- **Energy load forecasting**: Predict electricity demand and renewable energy production.
- **Manufacturing output planning**: Optimize production schedules.
- **Website traffic forecasting**: Plan for infrastructure needs based on traffic predictions.
- **IoT sensor forecasting**: Predict values from IoT devices for preventive maintenance.
- **Budget planning**: Forecast expenses and costs for better budget allocation.

## Integration with AWS Services

- **[[Amazon S3]]**: Store input data and forecast results.
- **[[AWS Identity and Access Management (IAM)]]**: Control access to forecast resources.
- **[[AWS CloudTrail]]**: Monitor API calls for auditing.
- **[[Amazon CloudWatch]]**: Monitor Forecast service metrics and logs.
- **[[AWS Glue]]**: ETL for forecast data preparation.
- **[[Amazon QuickSight]]**: Visualize forecast results.
- **[[Amazon SageMaker]]**: Integrate forecasts into broader ML workflows.
- **[[AWS Lambda]]**: Automate forecast generation and processing.
- **[[Amazon EventBridge]]**: Create event-driven forecast pipelines.
- **[[AWS Step Functions]]**: Orchestrate complex forecast workflows.

## Benefits

- **Accuracy**: Achieve up to 50% more accurate forecasts than traditional methods.
- **Ease of use**: No machine learning expertise required.
- **Scalability**: Scale from hundreds to millions of time series.
- **Speed**: Reduce forecast generation time from months to hours.
- **Cost-effectiveness**: Pay only for what you use without upfront costs.
- **Transparency**: Understand what factors influence your forecasts.
- **Low maintenance**: Fully managed service with automatic updates.
- **Customization**: Incorporate domain-specific knowledge.
- **Production-ready**: Built-in monitoring, versioning, and deployment.
- **Security**: Secure data handling with encryption and IAM integration.

## Pricing

Amazon Forecast pricing is based on:

- **Generated forecasts**: Pay per number of forecast time points.
- **Training hours**: Pay for compute time used during model training.
- **Storage**: Pay for storing datasets in Amazon Forecast.

Specific rates vary by region. A free tier is available for new users that includes a certain amount of training hours, forecast generations, and storage each month.