---
group:
  - notes
---
Security is fundamental with any AWS deployment. And with that in mind, I want to highlight a couple of points related specifically to EC2 security. When creating an [[Amazon EC2]] instance, you’ll be asked to select a security group for your instance.

A security group is essentially an instance-level firewall allowing you to restrict both ingress and egress traffic to your instance by specifying what traffic is allowed to communicate with it. You can restrict this communication by source ports and protocols for both inbound and outbound communication. Your instances are then associated with this security group, which can then be associated with other instances.

>[!Abstract] Learn More:
For more information about security groups, I encourage you to check out this lecture in our existing course: Working with AWS Networking and Amazon VPC

Security Groups.

When creating an EC2 instance, you’ll also need to select an existing key pair or create and download a new one.

But what is a key pair and what’s it used for? As the name implies, a key pair consists of a pair of keys: a public key and a private key. Key pairs are used to encrypt the login information for Linux and Windows EC2 instances, then decrypt that same information, allowing you to authenticate to the instance. The public key is used to encrypt data, such as the username and password. For Windows instances, the private key is used to decrypt this data, allowing you to gain access to the login credentials including the password. For Linux instances, the private key is used to remotely connect to the instance using SSH.

The public key is held and kept by AWS, but the private key is your responsibility to keep and ensure that it is never lost or compromised. If you choose to create a new key pair for your EC2 instance, it will download to your local machine after you create it.

Once you’ve done this, you must keep that file safe until you’re ready to connect to the associated EC2 instance. It’s worth noting that you can use the same key pair for multiple instances to save you from having to manage multiple private keys. Keep in mind, however, that should your private key become compromised, access could be gained to any instances where that key pair is used.

After you’ve authenticated to your EC2 instance for the first time, you can set up additional, less-privileged access controls such as local Windows accounts, allowing other users to connect and authenticate to your instance.

One final point regarding security on your EC2 instance: remember that it’s your responsibility to maintain and install the latest OS and security patches released by the OS vendor as dictated by the AWS Shared Responsibility Model.

>[!Abstract] Learn More:
For more information about the AWS Shared Responsibility Model, I encourage you to check out this resource: AWS Shared Responsibility Model.

That brings me to the end of this lecture. I hope you’ve enjoyed this introduction to EC2. Thank you so much for your time, and best of luck with your continued learning.