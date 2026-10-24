---
group:
  - technology
---
The AWS Command Line Interface (AWS CLI) is a unified tool to manage your AWS services from the command line. With just one tool to download and configure, you can control multiple AWS services from the command line and automate them through scripts.

## Key Features

- **Unified interface**: Control multiple AWS services from a single command-line tool.
- **Direct API access**: Execute commands that map to the AWS API.
- **Multi-platform support**: Available for Windows, macOS, and Linux.
- **IAM integration**: Use IAM credentials for secure service access.
- **Profiles**: Configure multiple credential sets for different AWS accounts.
- **Command completion**: Tab completion for commands and parameters.
- **Command history**: Review previously executed commands.
- **Parameter validation**: Validate input parameters before sending requests.
- **Wait commands**: Wait for specific resource states before proceeding.
- **Output formatting**: Control output format (JSON, YAML, text, table).
- **Pagination control**: Manage response pagination for large result sets.
- **Shorthand syntax**: Simplified parameter input for complex structures.
- **S3 commands**: Enhanced commands for Amazon S3 operations.
- **High-level commands**: Abstracted commands for common operations.
- **Wire logging**: Debug API calls by viewing raw HTTP requests and responses.
- **Configurable retries**: Customize retry behavior for transient failures.

## CLI Versions

- **AWS CLI v2**: The latest version with improved features and performance.
- **AWS CLI v1**: The original version, still maintained but with fewer features.

## Installation Methods

- **Direct download**: Installers and packages for various operating systems.
- **Package managers**: Installation via pip, apt, yum, etc.
- **Docker container**: Pre-built Docker image with AWS CLI installed.
- **Virtual environments**: Installation in Python virtual environments.
- **AWS CloudShell**: Pre-installed in the AWS CloudShell environment.

## Configuration Options

- **Configuration files**: Settings stored in `~/.aws/config` and `~/.aws/credentials`.
- **Environment variables**: Override settings using environment variables.
- **Command-line options**: Override settings using command-line parameters.
- **Instance profiles**: Use IAM roles for EC2 instances.
- **SSO integration**: Authentication using AWS Single Sign-On.
- **MFA support**: Multi-factor authentication for enhanced security.
- **External credential processes**: Custom credential acquisition scripts.
- **Credential providers**: Extensible credential resolution system.

## Common Use Cases

- **Resource management**: Create, modify, and delete AWS resources.
- **Infrastructure automation**: Incorporate AWS operations in scripts and tools.
- **CI/CD pipelines**: Automate AWS tasks in continuous integration workflows.
- **Batch operations**: Perform operations on multiple resources.
- **Data transfers**: Efficiently move data to and from AWS services.
- **Monitoring and reporting**: Query and process AWS resource data.
- **DevOps workflows**: Streamline development and operations tasks.
- **Custom tools**: Build custom tools and utilities on top of AWS CLI.
- **Cross-account management**: Manage resources across multiple AWS accounts.
- **Emergency response**: Execute pre-defined commands during incidents.

## Advanced Features

- **Aliases**: Create shortcuts for frequently used commands.
- **Paging**: Control output pagination for large responses.
- **Query language**: Filter and extract specific information from responses.
- **Auto-prompt**: Interactive help and prompting for commands.
- **Wizards**: Guided assistance for complex operations.
- **DynamoDB operations**: Enhanced commands for DynamoDB data manipulation.
- **S3 directory-like commands**: Recursive operations on S3 objects.
- **CloudFormation helpers**: Simplify CloudFormation stack management.
- **Waiters**: Commands that wait for resources to reach specific states.
- **Dry-run mode**: Preview API calls without making actual changes.

## Integration with AWS Services

The AWS CLI provides commands for virtually all AWS services, including:
- **Amazon EC2**: Manage compute instances and related resources.
- **Amazon S3**: Manipulate objects and buckets.
- **AWS IAM**: Manage users, groups, roles, and policies.
- **Amazon RDS**: Control database instances.
- **AWS Lambda**: Deploy and invoke serverless functions.
- **Amazon DynamoDB**: Interact with NoSQL databases.
- **AWS CloudFormation**: Create and manage infrastructure as code.
- **Amazon CloudWatch**: Monitor resources and applications.
- **AWS Organizations**: Manage multi-account environments.

## Benefits

- **Efficiency**: Automate repetitive tasks and operations.
- **Consistency**: Execute commands consistently across environments.
- **Scriptability**: Incorporate AWS operations in scripts and tools.
- **Reduced learning curve**: Use a single interface for multiple services.
- **Cross-platform**: Run the same commands on different operating systems.
- **Developer productivity**: Faster access to AWS services.
- **Automation**: Integrate AWS operations into automated workflows.
- **Flexibility**: Choose between GUI console and command-line interface.
- **Cost effectiveness**: Reduce manual operations and human error.

## Pricing

The AWS CLI is available at no additional cost. You are only charged for the AWS resources you create and use through the CLI, based on the standard pricing for those services.