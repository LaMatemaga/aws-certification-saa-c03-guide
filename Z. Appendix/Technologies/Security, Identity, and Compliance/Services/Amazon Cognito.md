---
group:
  - technology
---
Amazon Cognito is a customer identity and access management (CIAM) service that enables you to add user sign-up, sign-in, and access control to your web and mobile applications. It scales to millions of users and supports sign-in with social identity providers and enterprise identity providers via standard protocols.

## Key Components

### User Pools

Authentication service for application users:

- **User directory management**: Create and maintain a user directory.
- **Authentication flows**: Support for various authentication methods.
- **Security features**: MFA, account takeover protection, phone and email verification.
- **Customizable UI**: Hosted UI for sign-up and sign-in or customize with SDKs.
- **Standards compliance**: Support for OAuth 2.0, OIDC, and SAML 2.0.
- **Social identity federation**: Sign in with Facebook, Google, Amazon, and Apple.
- **Enterprise identity federation**: Integration with SAML and OIDC providers.
- **Custom authentication challenges**: Add application-specific authentication.

### Identity Pools

Authorization service for accessing AWS resources:

- **Temporary AWS credentials**: Secure access to AWS services.
- **Fine-grained access control**: Define permissions based on user identity.
- **Guest access**: Allow unauthenticated access to certain resources.
- **Identity federation**: Use identities from User Pools or external providers.
- **Developer authenticated identities**: Support for your existing authentication process.

## Security Features

- **Multi-factor authentication (MFA)**: SMS and TOTP-based MFA options.
- **Advanced security features**: Risk-based adaptive authentication, compromised credential checking.
- **Encryption**: Data encryption in transit and at rest.
- **Compliance**: Support for various compliance programs.
- **Access control**: IAM roles and policies for resource access.
- **User device tracking**: Track devices used to sign in.

## Common Use Cases

- **Consumer applications**: Add authentication to B2C applications.
- **SaaS applications**: Manage customer identities for SaaS solutions.
- **Mobile apps**: Add social sign-in and MFA to mobile apps.
- **Single page applications (SPAs)**: Add secure authentication to SPAs.
- **API authorization**: Secure access to your APIs.
- **Serverless applications**: Add authentication to serverless apps.
- **Multi-tenant applications**: Manage identities across multiple tenants.
- **Federated identity management**: Integrate with existing identity providers.

## Integration with AWS Services

- [[AWS API Gateway]]
- [[AWS AppSync]]
- [[AWS Lambda]]
- [[AWS Amplify]]
- [[Amazon S3]]
- [[Amazon DynamoDB]]
- Other AWS services via identity pools

## Benefits

- **Reduced development time**: Add authentication without building it yourself.
- **Scalability**: Handle millions of users without infrastructure management.
- **Security**: Implement security best practices out of the box.
- **Flexibility**: Support for multiple identity providers and custom workflows.
- **Cost-effectiveness**: Pay only for active users.
- **Compliance**: Support for multiple compliance frameworks.

## Pricing

Amazon Cognito pricing is based on:

- **User Pools**: Monthly active users, with a free tier of 50,000 monthly active users.
- **Identity Pools**: Requests made, with a free tier of 50,000 monthly active users.
- **Advanced security features**: Optional add-on priced per monthly active user.

There are no upfront commitments, and you only pay for what you use.