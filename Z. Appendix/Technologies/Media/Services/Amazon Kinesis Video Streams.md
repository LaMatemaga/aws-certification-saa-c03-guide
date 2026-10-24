---
group:
  - technology
---
Amazon Kinesis Video Streams is a fully managed AWS service that makes it easy to securely stream video from connected devices to AWS for analytics, machine learning (ML), playback, and other processing. It automatically provisions and elastically scales all the infrastructure needed to ingest streaming video data from millions of devices.

## Key Features

- **Secure ingestion**: Stream video securely from millions of devices.
- **Durable storage**: Store, encrypt, and index video data in durable streams.
- **Real-time and batch processing**: Access video data in real-time or batch mode.
- **Time-indexed metadata**: Attach time-indexed metadata to video frames.
- **WebRTC support**: Real-time peer-to-peer streaming with WebRTC.
- **Low-latency streaming**: Support for ultra-low latency applications.
- **Integration with ML services**: Connect to Amazon Rekognition and other ML services.
- **Media analytics**: Analyze video content for insights.
- **Industry standard protocols**: Support for RTSP, HTTPS, and WebRTC.
- **Client libraries**: SDKs for multiple platforms and languages.
- **Live and on-demand playback**: View live streams or recorded video.
- **Secure archiving**: Securely store video data for long periods.
- **Stream parser library**: Extract frames and metadata for processing.
- **Elastically scalable**: Automatically scales to handle varying workloads.

## Stream Types

- **Standard video streams**: For general video ingestion and processing.
- **WebRTC streams**: For real-time, interactive video applications.
- **Signaling channels**: For WebRTC offer/answer exchange.

## Supported Protocols and Formats

- **Ingestion protocols**: HTTPS, WebRTC, RTSP (via producer libraries)
- **Video formats**: H.264, H.265 (HEVC)
- **Audio formats**: AAC, G.711
- **Streaming formats**: HLS, DASH (via integration with Media Services)
- **Container formats**: MKV, MP4 (via parser library)

## Components and Architecture

- **Producers**: Devices or applications that stream video to Kinesis Video Streams.
- **Streams**: Resources that store and transport video data.
- **Consumers**: Applications that process or view video streams.
- **Stream parsers**: Tools to extract and process video frames.
- **Signaling channels**: Communication pathways for WebRTC setup.
- **Edge agent**: Optional component for edge processing and buffering.
- **Storage hierarchy**: Multi-tiered storage for cost-effective video retention.

## Common Use Cases

- **Smart home security**: Process video from security cameras.
- **Industrial automation**: Monitor and analyze industrial processes.
- **Smart cities**: Traffic management and public safety monitoring.
- **Media streaming**: Live and on-demand video delivery.
- **Video conferencing**: Real-time interactive video communication.
- **Computer vision applications**: ML-based analysis of video content.
- **Autonomous vehicles**: Process and analyze sensor data.
- **Healthcare monitoring**: Remote patient monitoring and analysis.
- **Retail analytics**: Customer behavior analysis in stores.
- **Remote assistance**: Interactive troubleshooting and support.

## Integration with AWS Services

- **Amazon Rekognition**: Video analysis for object, scene, and activity detection.
- **AWS Lambda**: Serverless computing for video processing.
- **Amazon SageMaker**: Build and train ML models with video data.
- **Amazon OpenSearch Service**: Search and analyze video metadata.
- **AWS IoT Core**: Connect with IoT devices and gateways.
- **Amazon S3**: Archive video data for long-term storage.
- **Amazon CloudFront**: Distribute video content globally.
- **Amazon EventBridge**: Trigger workflows based on video events.
- **Amazon SNS**: Notifications for video processing events.

## Benefits

- **Scalability**: Ingest and process video from millions of devices.
- **Security**: End-to-end encryption and IAM-based access control.
- **Durability**: Reliable storage for video data.
- **Fully managed**: No infrastructure to provision or maintain.
- **Real-time processing**: Process video as it's being streamed.
- **Flexible consumption**: Multiple ways to access and process video.
- **Cost-effective**: Pay only for what you use.
- **Time-synchronized data**: Correlate video with other time-series data.
- **Wide device support**: Libraries for various platforms and devices.
- **Built-in analytics**: Integration with AWS analytics services.

## Pricing

Amazon Kinesis Video Streams pricing is based on:

- **Data ingestion**: Pay per GB of data ingested.
- **Storage**: Pay per GB of data stored per month.
- **Consumption**: Pay per GB of data consumed.
- **WebRTC**: Pay per WebRTC peer connection minute.
- **Signaling**: Pay per signaling channel and per message.

There are no upfront costs or commitments, and pricing varies by AWS region. You only pay for the resources you actually use.