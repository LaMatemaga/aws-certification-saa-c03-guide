---
group:
  - technology
---
AWS WAF (Web Application Firewall) is a web application firewall that helps protect your web applications or APIs against common web exploits and bots that may affect availability, compromise security, or consume excessive resources. AWS WAF gives you control over how traffic reaches your applications by enabling you to create security rules that control bot traffic and block common attack patterns.

## Key Features

- **Web traffic filtering**: Create rules to filter web requests based on conditions you specify.
- **Protection against common attacks**: Shield against SQL injection, cross-site scripting (XSS), and other OWASP Top 10 vulnerabilities.
- **Bot control**: Identify and manage bot traffic with pre-configured and custom rules.
- **IP reputation lists**: Block requests from known malicious IP addresses.
- **Geolocation restrictions**: Block or allow requests based on country or region of origin.
- **Rate-based rules**: Automatically block IPs when request rates exceed thresholds.
- **Custom rules**: Create specific rules for your application's unique security needs.
- **Rule groups**: Reuse sets of rules across multiple web ACLs.
- **Managed rules**: Pre-configured rule sets maintained by AWS or AWS Marketplace sellers.
- **Real-time metrics and logging**: Monitor web requests and security events.
- **Full API support**: Automate security rule deployment and management.

## Protection Capabilities

- **Layer 7 (application layer) protection**: HTTP/HTTPS traffic filtering.
- **Request inspection**: Examine headers, query strings, URI paths, and request body.
- **IP address blocking**: Block requests from specific IP addresses or ranges.
- **Geographic restrictions**: Control access based on country or region.
- **Size constraints**: Limit size of specific parts of requests.
- **Rate limiting**: Control the rate of requests from any single IP address.
- **Regular expression matching**: Create complex pattern matching rules.
- **Managed protections**: Pre-configured rules for common vulnerabilities.

## AWS WAF Managed Rules

- **Core rule set**: Basic protections against common threats.
- **Admin protection**: Protects admin pages from unauthorized access.
- **Known bad inputs**: Blocks requests with known malicious inputs.
- **SQL database**: Protection against SQL injection attacks.
- **Linux operating system**: Protects Linux-specific vulnerabilities.
- **Windows operating system**: Protects Windows-specific vulnerabilities.
- **PHP application**: Protects PHP application vulnerabilities.
- **WordPress application**: Protects WordPress application vulnerabilities.

## Service Integrations

- **Amazon CloudFront**: Protect global content delivery.
- **Application Load Balancer**: Protect HTTP/HTTPS applications.
- **Amazon API Gateway**: Protect REST APIs.
- **AWS AppSync**: Protect GraphQL APIs.
- **AWS Firewall Manager**: Centrally manage WAF rules across accounts.
- **Amazon CloudWatch**: Monitor and alert on WAF metrics.
- **Amazon Cognito**: Add WAF protection to user pools.

## Common Use Cases

- **Web application protection**: Protect websites from common vulnerabilities.
- **API security**: Secure API endpoints against attacks and misuse.
- **Bot management**: Control and mitigate bot traffic.
- **DDoS mitigation**: Complement AWS Shield with application layer protection.
- **Compliance requirements**: Help meet security requirements for web applications.
- **Zero-day vulnerability protection**: Create emergency rules to address new threats.
- **Account takeover prevention**: Identify and block account takeover attempts.
- **Application layer DDoS mitigation**: Block application layer DDoS attacks.

## Benefits

- **Improved security posture**: Protect applications from known vulnerabilities.
- **Customizable protection**: Create rules specific to your application needs.
- **Visibility**: Gain insights into web traffic patterns and attacks.
- **Fast deployment**: Deploy rules in minutes to respond to threats.
- **Integration**: Seamless integration with AWS services.
- **Scalability**: Automatically scales with your application traffic.
- **Managed updates**: AWS-managed rules are updated as new vulnerabilities emerge.

## Pricing

AWS WAF pricing is based on:

- Number of web ACLs deployed
- Number of rules added to your web ACLs
- Number of web requests inspected

There are no upfront commitments, and you only pay for what you use.