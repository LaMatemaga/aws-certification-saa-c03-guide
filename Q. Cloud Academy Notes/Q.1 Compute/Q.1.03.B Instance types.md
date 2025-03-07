---
group:
  - notes
---
Now let’s take a look at instance types. Once you’ve selected your AMI from any of the different sources we’ve just discussed, you must then select an instance type. An instance type simply defines the size of the instance based on a number of different parameters, including:
- vCPUs, which are the number of virtual CPUs on the instance
- Architecture, which is the processor architecture, such as i386, x86, or ARM
- Memory, or the number of gigabytes of RAM associated with the instance
- Storage, which shows the capacity of any local instance store volumes, if available on the instance, as well as 
- Storage type, which indicates whether the instance store volumes are magnetic hard disks or SSDs, and
- Network performance, which shows the performance level or rate of data transfer

The key parameters to know for general usage of an EC2 instance could be summarized as vCPUs, memory, instance storage, and network performance. But this really depends on your actual use case. Having the flexibility to choose between hundreds of instance types allows you to select the most appropriate size or capability of an instance that you need for optimal performance within your applications. These different instance types are categorized into different families that offer distinct performance benefits, which again helps you to select the most appropriate instance for your needs. Within each of these instance families you will have a range of instance types with different CPU, memory, storage, and network performance. These instance families can be summarized as follows:
- **General Purpose**, which have a balanced mix of CPU, memory, and storage, making them ideal for small to medium databases, test and development environments, or web servers.
- **Compute Optimized**, which have a greater focus on compute power and are ideal for applications requiring high performance processors, such as batch processing or machine learning.
- **Memory Optimized**, which are primarily used for large-scale enterprise class in-memory applications, such as performing real-time processing of unstructured data.
- **Accelerated Computing**, which utilize hardware accelerators or co-processors to perform floating-point calculations faster and more efficiently.
- **Storage Optimized**, which are optimized for enhanced storage. Instances in this family use SSD backed instance storage for low latency and very high input/output, or I/O performance, including very high IOPS which is input/output operations per second. These instances are useful for data file systems and log processing applications.
- And finally, **HPC Optimized**, which are designed for high performance computing, or HPC workloads.