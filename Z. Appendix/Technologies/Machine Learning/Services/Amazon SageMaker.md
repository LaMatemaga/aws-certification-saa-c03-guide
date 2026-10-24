---
group:
  - technology
---
Amazon SageMaker is a fully managed machine learning service that enables data scientists and developers to build, train, and deploy machine learning models quickly and with minimal effort. It provides all the components used for machine learning in a single toolset, making it easier to create high-quality models and get them to production faster.

## Key Features

### Build

- **Studio IDE**: Integrated web-based development environment.
- **Notebooks**: Jupyter notebooks for development.
- **Feature Store**: Repository for machine learning features.
- **Data Wrangler**: Prepare and transform data visually.
- **Clarify**: Detect bias in data and models.
- **Ground Truth**: Create labeled datasets.
- **Autopilot**: Automated machine learning.
- **JumpStart**: Pre-trained models and solution templates.
- **Canvas**: No-code ML model building.
- **RStudio**: Integrated development environment for R.

### Train

- **Training jobs**: Distributed training capabilities.
- **Hyperparameter tuning**: Automatic model optimization.
- **Managed Spot Training**: Cost-effective training on spot instances.
- **Debugger**: Monitor and debug training jobs.
- **Distributed training libraries**: Optimized for distributed workloads.
- **Experiments**: Track and compare training runs.
- **Checkpointing**: Save training progress.
- **Multi-model training**: Train multiple models efficiently.
- **Pipeline parallelism**: Split models across multiple devices.
- **Training Compiler**: Accelerate model training.

### Deploy

- **Endpoints**: Real-time inference with auto-scaling.
- **Batch transform**: Batch processing for predictions.
- **Serverless inference**: Pay-per-use prediction endpoints.
- **Multi-model endpoints**: Host multiple models on a single endpoint.
- **Asynchronous inference**: Process long-running predictions.
- **Inference recommender**: Right-size inference instances.
- **Model monitor**: Detect data and model drift.
- **Edge deployment**: Deploy models to edge devices.
- **Pipelines**: Automate ML workflows.
- **Neo**: Optimize models for specific hardware.

## Supported Frameworks

- **TensorFlow**: Deep learning framework.
- **PyTorch**: Deep learning framework.
- **MXNet**: Deep learning framework.
- **XGBoost**: Gradient boosting framework.
- **Scikit-learn**: Machine learning framework.
- **R**: Statistical computing framework.
- **Hugging Face**: Natural language processing models.
- **Chainer**: Deep learning framework.
- **SparkML**: Machine learning on Spark.
- **Custom algorithms**: Support for custom code.

## Model Types

- **Linear/logistic regression**: For prediction and classification.
- **Decision trees**: For classification and regression.
- **Random forests**: Ensemble of decision trees.
- **Gradient boosting machines**: Advanced ensemble methods.
- **K-means**: For clustering.
- **Principal component analysis**: For dimensionality reduction.
- **Convolutional neural networks**: For image processing.
- **Recurrent neural networks**: For sequence data.
- **Transformers**: For natural language processing.
- **Time series models**: For forecasting.
- **Reinforcement learning**: For agent-based learning.
- **Anomaly detection**: For identifying outliers.
- **Recommender systems**: For personalization.
- **Transfer learning**: Adapting pre-trained models.

## Common Use Cases

- **Computer vision**: Image classification, object detection, segmentation.
- **Natural language processing**: Text analysis, sentiment analysis, translation.
- **Time series forecasting**: Demand prediction, capacity planning.
- **Anomaly detection**: Fraud detection, equipment failure prediction.
- **Recommendation systems**: Product recommendations, content personalization.
- **Predictive maintenance**: Predict equipment failures before they occur.
- **Customer churn prediction**: Identify at-risk customers.
- **Price optimization**: Dynamic pricing strategies.
- **Document processing**: Intelligent document extraction and analysis.
- **Healthcare diagnostics**: Disease detection and diagnosis.
- **Speech recognition**: Convert speech to text.
- **Financial risk modeling**: Credit scoring, risk assessment.
- **Supply chain optimization**: Inventory management, logistics planning.
- **Quality control**: Automated visual inspection.

## Integration with AWS Services

- **[[Amazon S3]]**: Store data and models.
- **[[AWS Identity and Access Management (IAM)]]**: Control access to resources.
- **[[Amazon Elastic Container Registry (Amazon ECR)]]**: Store custom training containers.
- **[[Amazon CloudWatch]]**: Monitor training and deployment.
- **[[AWS Lambda]]**: Trigger inference or training.
- **[[AWS Step Functions]]**: Orchestrate ML workflows.
- **[[AWS Glue]]**: ETL for data preparation.
- **[[Amazon Athena]]**: Query data for analysis.
- **[[Amazon Redshift]]**: Data warehousing integration.
- **[[Amazon Kinesis]]**: Process streaming data.
- **[[AWS Auto Scaling]]**: Scale inference endpoints.
- **[[AWS Marketplace]]**: Find and sell ML algorithms and models.

## Benefits

- **Improved productivity**: Faster development with integrated tools.
- **Reduced complexity**: Fully managed infrastructure.
- **Cost optimization**: Pay only for resources used.
- **Model quality**: Built-in best practices and optimization.
- **Faster deployment**: Streamlined path to production.
- **Scalability**: Automatically scale training and inference.
- **Flexibility**: Support for multiple frameworks and languages.
- **Security**: Data encryption and access control.
- **Collaboration**: Team-based development.
- **Explainability**: Tools for model transparency and bias detection.

## Pricing

Amazon SageMaker pricing is based on:

- **Notebook instances**: Hourly rate for development environments.
- **Training**: Hourly rate for compute resources used during training.
- **Hosting**: Hourly rate for deployed endpoints.
- **Data processing**: Charges for data labeling and processing.
- **Additional features**: Specific rates for features like Feature Store, Pipelines, etc.

Specific rates vary by instance type and region. SageMaker offers a free tier for new users to explore its capabilities.