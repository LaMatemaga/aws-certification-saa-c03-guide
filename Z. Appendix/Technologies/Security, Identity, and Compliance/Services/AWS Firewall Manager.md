---
group:
  - technology
---
AWS Directory Service provides multiple ways to set up and run Microsoft Active Directory with other AWS services such as Amazon EC2, Amazon RDS for SQL Server, FSx for Windows File Server, and AWS applications like WorkSpaces. It allows you to use existing Active Directory or create a new standalone directory in the AWS Cloud.

## Directory Types

### AWS Managed Microsoft AD

A fully managed Microsoft Active Directory in the AWS Cloud:

- **Full AD domain services**: Supports domain joins, Group Policy, and single sign-on.
- **Trust relationships**: Create trust relationships with on-premises domains.
- **Schema extensions**: Support for extending AD schema.
- **Multi-region replication**: Deploy to multiple AWS regions.
- **AD administrative tools**: Use standard tools like ADUC and Group Policy Management Console.
- **MFA integration**: Support for multi-factor authentication.
- **Shared directory**: Share your directory with multiple AWS accounts.

### AD Connector

A directory proxy service to connect AWS applications to your existing on-premises Active Directory:

- **Directory proxy**: Forwards requests to your on-premises directory.
- **No directory data cached**: Directory data remains on-premises.
- **End-user authentication**: Connect AWS services to your existing directory.
- **MFA integration**: Support for multi-factor authentication.
- **Directory referral support**: Follow directory referrals to additional domain controllers.

### Simple AD

A low-scale, low-cost directory powered by Samba 4:

- **Basic Active Directory compatibility**: Core AD functionality.
- **LDAP compatibility**: Support for LDAP-aware applications.
- **User accounts**: Manage user accounts and group memberships.
- **Kerberos-based SSO**: Single sign-on capability.
- **Group policies**: Basic group policy support.
- **Limited to 5,000 users**: Suitable for small organizations.
- **No trust relationships**: Cannot establish trusts with other domains.

### Amazon Cognito User Pools

Managed user directory for web and mobile applications (see [[Amazon Cognito]] for details)

## AWS Service Integrations

- Amazon EC2 (Windows instances)
- Amazon RDS for SQL Server
- Amazon FSx for Windows File Server
- Amazon WorkSpaces
- Amazon WorkDocs
- Amazon WorkMail
- AWS Management Console
- AWS IAM Identity Center (Single Sign-On)
- Amazon QuickSight
- Amazon Chime
- Amazon Connect

## Common Use Cases

- **Windows workloads in AWS**: Run Windows-based applications that depend on Active Directory.
- **Hybrid cloud deployments**: Connect AWS resources to on-premises Active Directory.
- **User lifecycle management**: Centralize user identity management.
- **Directory-aware applications**: Support applications that need a directory service.
- **File and print services**: Support Windows file and print services.
- **Database authentication**: Integrate with directory-aware databases.
- **End-user computing**: Support virtual desktops and collaboration services.

## Benefits

- **Managed service**: Eliminate the operational overhead of running directory services.
- **High availability**: Deployed across multiple Availability Zones for reliability.
- **Security**: Secure communication and data encryption.
- **Scalability**: Scale to support thousands of users and devices.
- **Compatibility**: Works with existing Active Directory-aware applications.
- **Hybrid connectivity**: Connect cloud resources to on-premises directories.

## Pricing

AWS Directory Service pricing varies by directory type:

- **AWS Managed Microsoft AD**: Per hour per directory plus per GB of storage used.
- **AD Connector**: Per hour per connection.
- **Simple AD**: Per hour per directory.

Additional charges apply for multi-region replication and shared directories.