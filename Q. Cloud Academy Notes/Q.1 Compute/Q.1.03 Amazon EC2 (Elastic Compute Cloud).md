---
group:
  - notes
---
>[!todo] Notes
> Previous: [[Q.1.02 What is Compute in AWS]]

Hello, and welcome to this lecture where I will introduce the [[Amazon EC2]] service. EC2 is likely to be the first compute service you’ll encounter when working with AWS. It allows you to deploy virtual servers within your AWS environment, and most people will require an EC2 instance as part of at least one of their solutions. There are a number of elements involved in creating an EC2 instance, which I want to break down and explain. This will help us define how the EC2 service works and also answer a number of questions that you may have. The EC2 service can be broken down into the following components:

- [[Q.1.03.A Amazon Machine Images]], or AMIs
- [[Q.1.03.B Instance types]]
- [[Q.1.03.C Instance purchasing options]]
- [[Q.1.03.D Tenancy]]
- [[Q.1.03.E User data]]
- [[Q.1.03.F Storage options]]
- [[Q.1.03.G Security]]


When configuring a new EC2 instance, you’ll come across a section called User Data. This allows you to enter commands or a command script that will run during the first boot cycle of the instance. This is a great way to automatically perform functions at boot time, such as pulling down additional software to install from any software repositories you may have. You could also download and install the latest OS updates. For example, you could enter yum update dash y, which for a Linux instance will update its own software automatically at the time of boot.

When setting up a new EC2 instance, you’ll also be asked to select and configure your storage requirements. Selecting storage for your EC2 instance will depend on the type of instance selected, how you intend to use the instance, and how critical your data is. Storage for EC2 can be classified as either persistent or ephemeral, which means temporary. Persistent storage is available by attaching elastic block storage volumes using Amazon Elastic Block Store, or EBS. Ephemeral storage is created by some EC2 instances themselves using instance store volumes, which are local disks on the underlying physical host. Let’s look at each of these storage options in greater detail.

EBS volumes are separate devices from the EC2 instance itself, so they aren’t physically attached like ephemeral storage. EBS volumes are considered network-attached storage devices, which are then logically attached to the EC2 instance via the AWS network. This is similar to attaching an external hard drive to your home laptop or PC, where the external hard drive represents your EBS volume, and the PC represents your EC2 instance. The data on your EBS volumes is automatically replicated within the same availability zone for resiliency, which is managed by AWS. You can disconnect an EBS volume from your EC2 instance and the data will remain intact, allowing you to reattach it to another EC2 instance within the same availability zone if required. It’s also possible to take point-in-time snapshots that will backup all the data on an EBS volume to S3.

You can also implement encryption on your EBS volumes if needed. This can be done by default for all new EBS volumes and copies of snapshots you create by enabling encryption by default from within the EC2 dashboard in the AWS console. You can also choose to enable encryption on a per-volume basis instead.

EBS volumes can be created in different sizes and with different performance capabilities depending on your requirements. To learn more about EBS, I encourage you to check out this course: Introduction to Amazon Elastic Block Store (EBS).

Ephemeral storage, or instance-backed storage, is storage that is physically attached to the underlying host on which the EC2 instance resides. Unlike an EBS volume, you can’t detach an ephemeral instance store volume from an instance. So going back to our previous example, this is similar to your laptop or PC’s internal hard drive. There is one key difference here, though. With EC2 instances, all saved data on an instance store volume is lost as soon as the instance hibernates, is stopped, or is terminated. If you reboot your instance, then the data will remain. But if the instance hibernates, stops, or terminates, or if there’s any kind of hardware failure with the underlying disk, the data on that instance store volume will be lost forever. Because instance store volumes are physically attached, they’re extremely fast, which makes them great for storing cache data and other temporary content. But if you have data that you need to retain, you should use EBS volumes for persistent data storage instead.

For more information about EC2, EBS, and instance storage, and to gain some hands-on experience working with these services, I encourage you to check out this learning path:

Managing AWS Compute (EC2) & Block Storage (EBS).

Security is fundamental with any AWS deployment. And with that in mind, I want to highlight a couple of points related specifically to EC2 security. When creating an EC2 instance, you’ll be asked to select a security group for your instance.

A security group is essentially an instance-level firewall allowing you to restrict both ingress and egress traffic to your instance by specifying what traffic is allowed to communicate with it. You can restrict this communication by source ports and protocols for both inbound and outbound communication. Your instances are then associated with this security group, which can then be associated with other instances. For more information about security groups, I encourage you to check out this lecture in our existing course Working with AWS Networking and Amazon VPC:

Security Groups.

When creating an EC2 instance, you’ll also need to select an existing key pair or create and download a new one.

But what is a key pair and what’s it used for? As the name implies, a key pair consists of a pair of keys: a public key and a private key. Key pairs are used to encrypt the login information for Linux and Windows EC2 instances, then decrypt that same information, allowing you to authenticate to the instance. The public key is used to encrypt data, such as the username and password. For Windows instances, the private key is used to decrypt this data, allowing you to gain access to the login credentials including the password. For Linux instances, the private key is used to remotely connect to the instance using SSH.

The public key is held and kept by AWS, but the private key is your responsibility to keep and ensure that it is never lost or compromised. If you choose to create a new key pair for your EC2 instance, it will download to your local machine after you create it.

Once you’ve done this, you must keep that file safe until you’re ready to connect to the associated EC2 instance. It’s worth noting that you can use the same key pair for multiple instances to save you from having to manage multiple private keys. Keep in mind, however, that should your private key become compromised, access could be gained to any instances where that key pair is used.

After you’ve authenticated to your EC2 instance for the first time, you can set up additional, less-privileged access controls such as local Windows accounts, allowing other users to connect and authenticate to your instance.

One final point regarding security on your EC2 instance: remember that it’s your responsibility to maintain and install the latest OS and security patches released by the OS vendor as dictated by the AWS Shared Responsibility Model. For more information about the AWS Shared Responsibility Model, I encourage you to check out this resource: AWS Shared Responsibility Model.

That brings me to the end of this lecture. I hope you’ve enjoyed this introduction to EC2. Thank you so much for your time, and best of luck with your continued learning.