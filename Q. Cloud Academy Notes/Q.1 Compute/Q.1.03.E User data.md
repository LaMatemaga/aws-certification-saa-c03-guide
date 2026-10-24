---
group:
  - notes
---
When configuring a new [[Amazon EC2]] instance, you’ll come across a section called User Data.

User Data allows you to enter commands or a command script that will run during the first boot cycle of the instance.
- Perform functions at boot time, such as pulling down additional software to install from any software repositories you may have.
- Download and install the latest OS updates.

>[!todo] Example
> You can enter this code that will update its own software automatically at the time of the boot for a Linux instance
> ```bash
> yum update -y
> ```
