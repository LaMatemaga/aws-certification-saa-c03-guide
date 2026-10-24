---
group:
  - technology
---
Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency and high transfer speeds. CloudFront is integrated with AWS – both physical locations that are directly connected to the AWS global infrastructure, as well as software that works seamlessly with services like AWS Shield for DDoS mitigation, Amazon S3, Elastic Load Balancing, and Amazon EC2.

## Key Features

- **Global edge network**: Deliver content through 410+ points of presence (PoPs) in 90+ cities across 48 countries.
- **Content caching**: Cache content at edge locations to reduce load on origin servers.
- **Origin failover**: Automatic failover to backup origins for high availability.
- **Custom SSL certificates**: Use your own SSL/TLS certificates for HTTPS connections.
- **Field-level encryption**: Additional layer of security for sensitive data.
- **Origin access controls**: Restrict access to S3 buckets and custom origins.
- **Real-time logs**: Receive logs in real-time for monitoring and analysis.
- **Cache behaviors**: Configure caching based on URL patterns, HTTP methods, and more.
- **Edge computing**: Run code closer to users with Lambda@Edge and CloudFront Functions.
- **Origin Shield**: Additional caching layer to reduce load on origins.
- **IPv6 support**: Deliver content to IPv6 users without any configuration changes.
- **Geo-restriction**: Control access to content based on user location.
- **HTTP/3 (QUIC) support**: Improved performance with the latest HTTP protocol.
- **Compression**: Automatically compress content to reduce transfer size.

## Content Types Supported

- **Static content**: HTML, CSS, JavaScript files, images, etc.
- **Dynamic content**: API responses, web applications, etc.
- **Video streaming**: Live and on-demand video using various streaming protocols.
- **Software distributions**: Large file downloads like software updates.
- **API acceleration**: Improved performance for API calls.
- **Game assets**: Faster delivery of game updates and content.

## Edge Computing Options

- **CloudFront Functions**: Lightweight JavaScript functions for high-scale, latency-sensitive CDN customizations.
- **Lambda@Edge**: More complex functions with access to additional AWS services.

## Security Features

- **AWS Shield Standard**: Basic DDoS protection included at no additional cost.
- **AWS WAF integration**: Web application firewall to protect against common web exploits.
- **HTTPS support**: Secure end-to-end encryption for content delivery.
- **Access controls**: Signed URLs and signed cookies for private content.
- **Field-level encryption**: Encrypt specific data fields throughout the processing chain.
- **Geo-restriction**: Block users in specific geographic locations.

## Common Use Cases

- **Website acceleration**: Improve global performance of websites and applications.
- **Software distribution**: Distribute software updates efficiently.
- **Video streaming**: Deliver live and on-demand video content globally.
- **API acceleration**: Improve API performance and reduce latency.
- **Game delivery**: Deliver game assets and updates to global users.
- **Static and dynamic content delivery**: Deliver a mix of static and dynamic content.
- **Security and DDoS protection**: Protect web applications while improving performance.
- **Mobile content delivery**: Optimize content delivery to mobile users.

## Benefits

- **Improved performance**: Reduce latency by serving content from locations closer to users.
- **High availability**: Multiple edge locations ensure reliable content delivery.
- **Cost-effective**: Pay only for what you use with no upfront commitments.
- **Scalability**: Automatically handle traffic spikes without provisioning.
- **Security**: Integrated security features protect your content and users.
- **Programmability**: Customize content delivery with serverless computing.
- **Easy to implement**: Simple to set up with AWS services or custom origins.

## Pricing

Amazon CloudFront pricing is based on:

- Data transfer out to the internet
- Number of HTTP/HTTPS requests
- Invalidation requests (first 1,000 paths per month are free)
- Real-time logs
- Edge computing usage (CloudFront Functions and Lambda@Edge)

CloudFront offers a free tier for new AWS customers, and pricing varies by geographic region.