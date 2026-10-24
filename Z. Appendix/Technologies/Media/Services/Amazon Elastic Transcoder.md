---
group:
  - technology
---
Amazon Elastic Transcoder is a highly scalable, easy to use and cost-effective media transcoding service in the cloud. It allows you to convert media files from their source format into versions that will play back on devices like smartphones, tablets, and PCs.

## Key Features

- **Scalable transcoding**: Automatically scales to handle your transcoding jobs.
- **Preset management**: Pre-defined transcoding settings for popular output formats.
- **Custom presets**: Create custom presets for specific transcoding requirements.
- **Job management**: Queue, prioritize, and manage transcoding jobs.
- **Progress monitoring**: Track the status of your transcoding jobs.
- **Thumbnails generation**: Create thumbnails from your video files.
- **Watermarking**: Add watermarks to your video content.
- **Clip stitching**: Combine multiple clips into a single output.
- **Captions**: Support for closed captions.
- **Digital Rights Management (DRM)**: Apply DRM to protect your content.
- **Notifications**: Receive notifications about job status via Amazon SNS.
- **Encryption**: Protect your content with encryption.
- **Fault tolerance**: Automatically handles infrastructure failures.

## Supported Input Formats

- **Video containers**: 3GP, AVI, FLV, MP4, MPEG-1, MPEG-2, MKV, MXF, OGG, WebM, etc.
- **Video codecs**: H.264, AAC, etc.
- **Audio containers**: FLAC, MP3, MP4, OGG, WAV, WebM, etc.
- **Image formats**: GIF, JPG, PNG

## Supported Output Formats

- **Video containers**: FLAC, FLV, MP3, MP4, MPEG-TS, OGG, WebM, etc.
- **Video codecs**: H.264, VP8, VP9, etc.
- **Audio codecs**: AAC, FLAC, MP3, Vorbis, etc.
- **HLS and DASH**: Packaging for adaptive bitrate streaming.
- **Thumbnails**: JPG, PNG

## System Architecture

- **Pipelines**: Processing queues that manage transcoding jobs.
- **Jobs**: Individual transcoding tasks.
- **Presets**: Settings that specify the output format and parameters.
- **Notifications**: Events that inform you about job status changes.
- **IAM integration**: Fine-grained access control to Elastic Transcoder resources.
- **S3 integration**: Source and destination storage using Amazon S3.

## Common Use Cases

- **Media libraries**: Convert videos to multiple formats for different devices.
- **User-generated content**: Transcode user uploads to standardized formats.
- **Video on demand (VOD)**: Prepare content for video-on-demand services.
- **Mobile video delivery**: Optimize videos for mobile devices.
- **Adaptive bitrate streaming**: Create content for adaptive streaming protocols.
- **Format migration**: Convert legacy content to modern formats.
- **Content protection**: Apply DRM and encryption to protect content.
- **Archival preparation**: Prepare content for long-term archival.
- **Social media publishing**: Format videos for various social media platforms.

## Integration with AWS Services

- **Amazon S3**: Source and destination storage for media files.
- **AWS Lambda**: Trigger transcoding jobs automatically based on events.
- **Amazon SNS**: Notifications about job status.
- **Amazon CloudWatch**: Monitor transcoding activity.
- **AWS Identity and Access Management**: Control access to transcoding resources.
- **Amazon CloudFront**: Distribute transcoded content globally.

## Benefits

- **Scalability**: Automatically scales to handle your transcoding needs.
- **Simplified workflow**: Easy-to-use API and console.
- **Cost-effective**: Pay only for the transcoding you use.
- **High-quality outputs**: Professional-grade transcoding quality.
- **Broad format support**: Support for numerous input and output formats.
- **No infrastructure to manage**: Fully managed service with no servers to provision.
- **Integration with AWS ecosystem**: Works seamlessly with other AWS services.
- **Reliability**: Built on AWS's highly reliable infrastructure.

## Pricing

Amazon Elastic Transcoder pricing is based on:

- **Minutes transcoded**: Cost per minute of output content.
- **Resolution tiers**: Different rates for SD, HD, and audio-only transcoding.
- **Storage and transfer**: Standard Amazon S3 rates apply for storage and data transfer.

There are no upfront commitments or minimum fees, and you only pay for what you use. Pricing varies by AWS region.

> **Note**: While Amazon Elastic Transcoder is still supported, AWS now recommends AWS Elemental MediaConvert for new media processing workflows. MediaConvert offers more advanced features and broader codec support.