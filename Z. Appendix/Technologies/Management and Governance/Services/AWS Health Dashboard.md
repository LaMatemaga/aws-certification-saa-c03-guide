---
group:
  - technology
---
AWS Health Dashboard (also known as AWS Personal Health Dashboard or AWS Health) provides personalized visibility into the performance and availability of the AWS services underlying your AWS resources. It gives you a personalized view into the status of AWS services that power your applications, along with contextualized information to help you understand and manage events in progress.

## Key Features

- **Personalized service health**: View of AWS service health specific to your resources.
- **Proactive notifications**: Advance notifications for scheduled activities.
- **Detailed event information**: Contextual information about service events.
- **Resource-specific information**: Impact details for your specific AWS resources.
- **Historical event data**: Access to past events affecting your resources.
- **Organizational view**: Aggregated health events across AWS Organizations accounts.
- **Event filtering**: Filter health events by service, region, account, and more.
- **Programmatic access**: API and SDK access to health information.
- **Event management**: Manage and track the resolution of events.
- **Integration capabilities**: Connect with monitoring and incident management systems.
- **Health event notifications**: Receive alerts through various channels.
- **Change management**: Visibility into upcoming changes to AWS services.
- **Maintenance notifications**: Information about scheduled maintenance.
- **End-of-life announcements**: Notifications about service or feature retirements.

## Dashboard Components

- **Service Health**: Current status of AWS services globally or by region.
- **Your Account Health**: Events specific to your AWS account and resources.
- **Planned Changes**: Upcoming changes to AWS services that might affect you.
- **Other Notifications**: Additional information relevant to your AWS usage.
- **Event Log**: Historical record of health events affecting your account.
- **Affected Resources**: Specific AWS resources impacted by events.
- **Event Details**: Comprehensive information about each health event.
- **Organizational View**: Health events across your AWS organization.

## Event Categories

- **Issue**: Events that indicate a service is experiencing problems.
- **Scheduled Change**: Upcoming changes to AWS services that may require action.
- **Account Notification**: Important information about your AWS account.
- **Investigation**: Events where AWS is investigating a potential issue.
- **Maintenance**: Planned maintenance that may affect service availability.
- **Recovery**: Information about service recovery after an event.
- **Security**: Security-related notifications and advisories.
- **Risk**: Potential risks that might affect your resources.

## AWS Health API

- **DescribeEvents**: Retrieve information about health events.
- **DescribeEventDetails**: Get detailed information about specific events.
- **DescribeAffectedEntities**: Find AWS resources affected by an event.
- **DescribeEventAggregates**: Get event counts grouped by filter criteria.
- **DescribeEntityAggregates**: Get affected entity counts for events.
- **DescribeEventTypes**: Information about event type categories.
- **DescribeHealthServiceStatusForOrganization**: Check if organizational view is enabled.
- **EnableHealthServiceAccessForOrganization**: Turn on organizational view.
- **DisableHealthServiceAccessForOrganization**: Turn off organizational view.

## Common Use Cases

- **Operational awareness**: Stay informed about AWS service disruptions.
- **Incident management**: Include AWS service health in your incident response.
- **Change management**: Plan for scheduled AWS service changes.
- **Resource impact assessment**: Identify which of your resources are affected by events.
- **Multi-account monitoring**: Monitor health events across your organization.
- **Automated event handling**: Build automation to respond to AWS Health events.
- **Service health reporting**: Include AWS service health in operational reports.
- **Compliance documentation**: Document service disruptions for compliance purposes.
- **SLA monitoring**: Track service availability for SLA compliance.
- **Root cause analysis**: Use event information in post-incident reviews.

## Integration with AWS Services

- **Amazon EventBridge**: Create rules to take action on AWS Health events.
- **AWS CloudWatch**: Combine with CloudWatch metrics for comprehensive monitoring.
- **AWS Organizations**: View health events across multiple accounts.
- **AWS CloudTrail**: Track AWS Health API activity.
- **AWS Lambda**: Automate responses to AWS Health events.
- **Amazon SNS**: Send notifications for health events.
- **AWS Chatbot**: Relay health notifications to Slack or Microsoft Teams.

## Benefits

- **Personalized visibility**: See only events that affect your resources.
- **Proactive notifications**: Receive advance notice of scheduled activities.
- **Reduced time to resolution**: Get contextual information to resolve issues faster.
- **Improved planning**: Prepare for upcoming changes or maintenance.
- **Centralized health tracking**: Monitor AWS service health across accounts.
- **Better incident management**: Incorporate AWS service health into your incident response.
- **Operational confidence**: Know when AWS services are functioning normally.
- **Efficient troubleshooting**: Distinguish between AWS issues and application issues.
- **Automated response**: Build event-driven automation for health events.

## Pricing

AWS Health Dashboard is available at no additional charge. The basic AWS Health Dashboard is available to all AWS customers, while the AWS Health API and organizational view features are available to customers with a Business, Enterprise On-Ramp, or Enterprise Support plan.