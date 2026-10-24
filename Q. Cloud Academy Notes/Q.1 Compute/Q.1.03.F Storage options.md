---
group:
  - notes
---
When setting up a new [[Amazon EC2]] instance, you’ll also be asked to select and configure your storage requirements. Selecting storage for your EC2 instance *will depend on the type of instance selected, how you intend to use the instance, and how critical your data is.*

Storage for EC2 can be classified as either persistent or ephemeral, which means temporary.
- **Persistent storage** is available by attaching elastic block storage volumes using [[Amazon Elastic Block Store (Amazon EBS)]].
- **Ephemeral storage** is created by some EC2 instances themselves using [[Instance store volumes]].

Let’s look at each of these storage options in greater detail.

## Persistent Storage

[[Amazon Elastic Block Store (Amazon EBS)]] volumes are separate devices from the EC2 instance itself, so they aren’t physically attached like ephemeral storage. EBS volumes are considered network-attached storage devices, which are then logically attached to the EC2 instance via the AWS network. This is similar to attaching an external hard drive to your home laptop or PC, where the external hard drive represents your EBS volume, and the PC represents your EC2 instance. The data on your EBS volumes is automatically replicated within the same availability zone for resiliency, which is managed by AWS. You can disconnect an EBS volume from your EC2 instance and the data will remain intact, allowing you to reattach it to another EC2 instance within the same availability zone if required. It’s also possible to take point-in-time snapshots that will backup all the data on an EBS volume to S3.

You can also implement encryption on your EBS volumes if needed. This can be done by default for all new EBS volumes and copies of snapshots you create by enabling encryption by default from within the EC2 dashboard in the AWS console. You can also choose to enable encryption on a per-volume basis instead.

EBS volumes can be created in different sizes and with different performance capabilities depending on your requirements.

>[!Abstract] Learn More:
To learn more about EBS, I encourage you to check out this course: Introduction to Amazon Elastic Block Store (EBS).

## Ephemeral Storage

Ephemeral storage, or instance-backed storage, is storage that is physically attached to the underlying host on which the EC2 instance resides. Unlike an EBS volume, you can’t detach an ephemeral instance store volume from an instance. So going back to our previous example, this is similar to your laptop or PC’s internal hard drive. There is one key difference here, though. With EC2 instances, all saved data on an instance store volume is lost as soon as the instance hibernates, is stopped, or is terminated. If you reboot your instance, then the data will remain. But if the instance hibernates, stops, or terminates, or if there’s any kind of hardware failure with the underlying disk, the data on that instance store volume will be lost forever. Because instance store volumes are physically attached, they’re extremely fast, which makes them great for storing cache data and other temporary content. But if you have data that you need to retain, you should use EBS volumes for persistent data storage instead.


>[!Abstract] Learn More:
For more information about EC2, EBS, and instance storage, and to gain some hands-on experience working with these services, I encourage you to check out this learning path: Managing AWS Compute (EC2) & Block Storage (EBS).