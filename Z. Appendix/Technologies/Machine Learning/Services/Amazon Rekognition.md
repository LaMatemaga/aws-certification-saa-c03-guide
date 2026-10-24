---
group:
  - technology
---
Amazon Rekognition is a cloud-based computer vision service that makes it easy to add image and video analysis to your applications. It provides powerful, pre-trained computer vision capabilities to extract information and insights from your images and videos, allowing you to analyze visual content without the need for specialized machine learning expertise.

## Key Features

### Image Analysis

- **Object and scene detection**: Identify thousands of objects and scenes.
- **Facial analysis**: Detect faces and analyze attributes like gender, age, emotions.
- **Face comparison**: Compare faces for similarity and verification.
- **Face search**: Search for specific faces in large collections.
- **Celebrity recognition**: Identify thousands of well-known personalities.
- **Text detection**: Extract text from images.
- **Content moderation**: Detect inappropriate or offensive content.
- **Image properties**: Analyze image quality, dominant colors, etc.
- **Custom labels**: Train custom models to detect specific objects.
- **Personal protective equipment detection**: Identify safety equipment usage.

### Video Analysis

- **Person tracking**: Track people through video frames.
- **Face tracking**: Track faces through video frames.
- **Person path tracking**: Follow movement patterns of individuals.
- **Face search in videos**: Find specific faces in video collections.
- **Celebrity recognition in videos**: Identify celebrities in videos.
- **Text detection in videos**: Extract text from video frames.
- **Content moderation in videos**: Detect inappropriate content.
- **Segment detection**: Identify logical segments in videos.
- **Shot detection**: Identify camera shot changes.
- **Technical cue detection**: Identify black frames, color bars, etc.

## Analysis Methods

- **Synchronous analysis**: Real-time processing for images and short videos.
- **Asynchronous analysis**: Process longer videos and larger collections.
- **Streaming analysis**: Real-time analysis of live video streams.
- **Batch processing**: Analyze large collections of media.
- **Storage-based processing**: Process media stored in Amazon S3.
- **Custom model training**: Create specialized detection models.
- **EdgeDeployment**: Deploy models to edge devices.

## Common Use Cases

- **Content moderation**: Filter inappropriate content on platforms.
- **Facial verification**: Authenticate users based on facial recognition.
- **Media indexing**: Catalog images and videos for searchability.
- **Sentiment analysis**: Analyze facial expressions for emotion.
- **Public safety**: Assist in finding missing persons or public safety monitoring.
- **Smart retail**: Analyze store traffic patterns and demographics.
- **Identity verification**: Verify identity for secure access.
- **Social media analysis**: Understand visual content on social platforms.
- **Warehouse safety**: Monitor PPE compliance in industrial settings.
- **Media and entertainment analysis**: Catalog and search media libraries.
- **Document analysis**: Extract text and information from documents.
- **Brand monitoring**: Track brand logo appearances in media.
- **Automated quality control**: Visual inspection in manufacturing.
- **Sports analytics**: Track player movements and game events.

## Integration with AWS Services

- **[[Amazon S3]]**: Process media stored in S3 buckets.
- **[[AWS Lambda]]**: Trigger analysis functions in response to events.
- **[[Amazon Kinesis Video Streams]]**: Analyze live video streams.
- **[[AWS Step Functions]]**: Orchestrate complex video processing workflows.
- **[[Amazon SageMaker]]**: Extend capabilities with custom ML models.
- **[[Amazon CloudWatch]]**: Monitor service usage and performance.
- **[[AWS IoT]]**: Enable visual intelligence at the edge.
- **[[Amazon Simple Notification Service (Amazon SNS)]]**: Receive notifications about analysis results.
- **[[Amazon EventBridge]]**: Create event-driven video analysis pipelines.
- **[[Amazon DynamoDB]]**: Store analysis results and metadata.

## Benefits

- **Accuracy**: High-quality models trained on diverse datasets.
- **Scalability**: Process from a few images to millions.
- **Cost-effectiveness**: Pay only for what you analyze.
- **Easy integration**: Simple APIs for adding vision to applications.
- **Continuous learning**: Models are regularly improved by AWS.
- **No ML expertise required**: Use pre-trained models without ML knowledge.
- **Customization**: Train custom models for specific use cases.
- **Comprehensive vision capabilities**: One service for multiple vision tasks.
- **Security**: Secure processing with encryption and IAM integration.
- **Global availability**: Available in most AWS regions.

## Pricing

Amazon Rekognition pricing is based on:

- **Image analysis**: Pay per image analyzed.
- **Video analysis**: Pay per minute of video analyzed.
- **Face storage**: Pay for storing face vectors for search.
- **Custom Labels**: Pay for training hours and inference units.

Specific rates vary by feature and region. A free tier is available for new users that includes a certain amount of image and video analysis each month.