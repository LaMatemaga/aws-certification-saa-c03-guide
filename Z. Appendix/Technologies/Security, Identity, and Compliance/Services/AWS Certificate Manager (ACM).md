---
group:
  - technology
---
AWS Certificate Manager is a service that lets you easily provision, manage, and deploy public and private SSL/TLS certificates for use with AWS services and your internal connected resources. It handles the complexity of creating, storing, and renewing certificates, eliminating the manual processes traditionally associated with certificate management.

## Key Features

- **Simplified certificate provisioning**: Request and deploy SSL/TLS certificates with just a few clicks.
- **Managed certificate renewal**: Automatic renewal of Amazon-issued certificates, eliminating expiration-related outages.
- **Integration with AWS services**: Seamless integration with services like Elastic Load Balancing, Amazon CloudFront, and API Gateway.
- **Public and private certificate authorities**: Support for both public certificates (for public endpoints) and private certificates (for internal resources).
- **Certificate validation**: Domain validation via email or DNS.
- **Wildcard and multi-domain certificates**: Support for securing multiple sub-domains with a single certificate.
- **Certificate import**: Import certificates from third-party issuers.
- **Certificate transparency logging**: Configurable logging options for public certificates.

## AWS Service Integrations

- Elastic Load Balancing
- Amazon CloudFront
- Amazon API Gateway
- AWS Elastic Beanstalk
- AWS AppSync
- AWS Nitro Enclaves
- Amazon Cognito User Pools
- AWS App Runner

## Certificate Types

- **Public certificates**: For public-facing websites and applications.
- **Private certificates**: For internal resources (requires AWS Private CA).
- **Imported certificates**: Certificates obtained from third-party certificate authorities.

## Common Use Cases

- **Secure websites**: Add HTTPS support to your websites and applications.
- **Secure API endpoints**: Add TLS to API Gateway APIs.
- **Secure internal communications**: Encrypt traffic between internal services using private certificates.
- **SSL/TLS for load balancers**: Configure secure listeners on load balancers.
- **Secure CloudFront distributions**: Secure content delivery with custom SSL certificates.
- **Certificate lifecycle management**: Automate the provisioning, renewal, and management of certificates.

## Benefits

- **Cost savings**: Public certificates issued by ACM are free.
- **Time savings**: Automate the certificate renewal process.
- **Reduced operational overhead**: Eliminate manual certificate management tasks.
- **Improved security**: Avoid outages due to expired certificates.
- **Simplified deployment**: Deploy certificates to supported services with a few clicks.

## Pricing

- **ACM certificates**: Public certificates issued by ACM are free of charge.
- **Private certificates**: Private certificates are priced based on the AWS Private CA usage fees.
- **Imported certificates**: No additional charge for importing certificates.

There are no monthly fees for using ACM to manage and deploy certificates.