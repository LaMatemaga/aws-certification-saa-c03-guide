---
group:
  - technology
---
Amazon Pinpoint is a flexible and scalable outbound and inbound marketing communications service. It enables you to connect with customers over channels like email, SMS, push notifications, voice, and in-app messaging. You can use Amazon Pinpoint to send targeted messages (such as promotional alerts and customer retention campaigns), as well as transactional messages (such as order confirmations and password reset notifications).

## Key Features

### Multi-channel Messaging

- **Email**: Send formatted and personalized email campaigns.
- **SMS**: Deliver text messages globally.
- **Push notifications**: Send notifications to mobile apps.
- **In-app messaging**: Display targeted messages within applications.
- **Voice messages**: Make automated voice calls with text-to-speech.
- **Custom channels**: Integrate with other communication channels.

### Audience Management

- **Audience segmentation**: Create targeted segments based on attributes and behaviors.
- **Dynamic segmentation**: Automatically update segments based on real-time data.
- **Import segments**: Import audience data from external sources.
- **User attributes**: Store and use custom user attributes.
- **Endpoint management**: Track multiple devices and channels per user.
- **User engagement history**: View messaging history for each user.
- **Audience export**: Export audience segments for use in other systems.

### Campaign Management

- **Campaign scheduling**: Set up one-time or recurring campaigns.
- **A/B testing**: Test different message variants.
- **Campaign analytics**: Track campaign performance metrics.
- **Message templates**: Create reusable message templates.
- **Variable substitution**: Personalize messages with user attributes.
- **Campaign journeys**: Create multi-step, multi-channel campaigns.
- **Direct messaging**: Send one-off messages to specific users.
- **Event-triggered campaigns**: Launch campaigns based on user actions.
- **Holdout groups**: Exclude control groups from campaigns.

### Analytics and Metrics

- **Delivery metrics**: Track successful deliveries and failures.
- **Engagement metrics**: Monitor opens, clicks, and conversions.
- **Funnel analysis**: Analyze user progression through funnels.
- **Custom event tracking**: Track application-specific events.
- **Standard metrics**: Pre-built analytics for common scenarios.
- **Custom metrics**: Define your own success metrics.
- **Real-time analytics**: View campaign results as they happen.
- **Cohort analysis**: Compare behavior across user groups.
- **Export analytics**: Export raw data for custom analysis.

### Personalization

- **Message variables**: Customize messages with user data.
- **Conditional content**: Display different content based on user attributes.
- **Personalized recommendations**: Include personalized product or content suggestions.
- **Machine learning integration**: Use Amazon ML services for advanced personalization.
- **Language customization**: Send messages in the user's preferred language.
- **Location-based personalization**: Customize content based on user location.
- **Time zone optimization**: Send messages in the user's local time zone.

## Common Use Cases

- **Customer engagement**: Nurture customer relationships through relevant communications.
- **Marketing campaigns**: Execute multi-channel marketing campaigns.
- **Transactional messaging**: Send order confirmations, shipping updates, etc.
- **User onboarding**: Guide new users through product adoption.
- **Promotional campaigns**: Announce new products, features, or sales.
- **Event notifications**: Inform users about relevant events.
- **Re-engagement campaigns**: Win back inactive users.
- **Automated workflows**: Trigger messages based on user actions or external events.
- **Appointment reminders**: Send automated reminders for upcoming appointments.
- **Loyalty programs**: Support customer loyalty initiatives.
- **Customer feedback collection**: Request and gather user feedback.
- **Account alerts**: Notify users about account activity or security issues.
- **Subscription management**: Handle subscription renewals and updates.
- **Abandoned cart reminders**: Remind users about incomplete purchases.

## Integration with AWS Services

- **[[Amazon Simple Email Service (SES)]]**: Send high-volume email campaigns.
- **[[Amazon Simple Notification Service (Amazon SNS)]]**: Deliver push notifications and SMS messages.
- **[[AWS Lambda]]**: Trigger custom logic for campaign execution.
- **[[Amazon S3]]**: Store and retrieve customer data and analytics.
- **[[Amazon Comprehend]]**: Analyze sentiment in customer feedback.
- **[[Amazon Personalize]]**: Add ML-powered personalization.
- **[[Amazon Lex]]**: Create interactive voice and chat experiences.
- **[[AWS Amplify]]**: Easy integration with mobile and web applications.
- **[[Amazon EventBridge]]**: Create event-driven messaging workflows.
- **[[Amazon Connect]]**: Integration with contact center capabilities.
- **[[AWS CloudFormation]]**: Automate Pinpoint resource provisioning.
- **[[Amazon Cognito]]**: Synchronize user data for authentication.

## Benefits

- **Cross-channel coordination**: Orchestrate messaging across multiple channels.
- **Targeted communications**: Reach the right audience with relevant messages.
- **Scalability**: Handle messaging from startups to enterprises.
- **Analytics-driven**: Use data to improve campaign effectiveness.
- **Personalization**: Deliver tailored experiences to each recipient.
- **Cost-effectiveness**: Pay only for what you use without upfront costs.
- **Global reach**: Deliver messages worldwide.
- **Compliance management**: Tools for honoring user preferences and regulatory requirements.
- **Deliverability management**: Optimize for high deliverability rates.
- **Flexible integration**: Connect with existing systems and data sources.
- **Developer-friendly**: Comprehensive APIs and SDKs.

## Pricing

Amazon Pinpoint pricing is based on:

- **Base charge**: Monthly charge per active targeted endpoint.
- **Channel-specific costs**:
    - **Email**: Pay per email sent.
    - **SMS**: Pay per SMS message part sent.
    - **Push notifications**: Pay per push notification delivered.
    - **Voice**: Pay per voice message minute.
    - **In-app messaging**: Pay per message.
- **Campaign and journey executions**: Pay per journey or campaign execution.
- **Additional charges**: May apply for premium SMS routes, dedicated phone numbers, etc.

Specific rates vary by region and volume. A free tier is available for new users that includes a certain amount of messages and endpoints each month.