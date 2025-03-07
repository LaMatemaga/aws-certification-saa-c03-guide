---
group:
  - notes
---
I want to begin by introducing AMIs, Amazon Machine Images. AMIs are essentially templates of pre-configured EC2 instances which allow you to quickly launch a new EC2 instance based on the configuration defined within the AMI. This prevents you from needing to install an operating system or any other common applications that you might need to install on a number of other EC2 instances. 

>[!abstract] Definition
> From a high-level perspective, an **Amazon Machine Image (AMI)** is an image baseline that includes an operating system and applications, along with any additional custom configuration. 

AWS provides a large number of AMIs covering different operating systems including:
- Amazon Linux
- macOS
- Ubuntu
- Microsoft Windows
- among others 

When configuring your EC2 instance, selecting an AMI is the first configuration choice you'll need to make. You can also create your own AMIs to help speed up your deployment process. For example, you would start by selecting an AWS AMI, perhaps Amazon Linux. And then, once it’s up and running, you may need to install a number of your own custom applications and make other specific configuration changes. Now let’s say you needed a second server to perform the same functionality. You could go through the same process of selecting the Amazon Linux AMI, and again manually installing the applications and making your configuration changes. Or, once you’ve made those changes on the first instance, you could then simply create a brand new AMI or template of that instance with all your applications installed and configuration changes already made. Then, if you need another instance of the same configuration, all you need to do is select your custom AMI as the base image for a new instance and it will launch with Amazon Linux, your custom applications already installed, and any configuration changes already made. As you can see, this approach has many benefits and especially comes in handy when implementing auto-scaling, where multiple instances of your baseline configuration may need to be spun up quickly to meet increasing levels of demand.

Now in addition to both AWS-managed and your own custom-managed AMIs, you could also select an AMI from the AWS Marketplace. The AWS Marketplace is essentially an online store that allows you to purchase AMIs from trusted vendors like:
- Cisco Systems
- F5
- Palo Alto Networks
- and others

These vendor AMIs have specific applications and configurations already made, such as instances that are optimized with built-in security and monitoring tools.

You can also choose from Community AMIs, which are public AMIs that can be created and shared by anyone.