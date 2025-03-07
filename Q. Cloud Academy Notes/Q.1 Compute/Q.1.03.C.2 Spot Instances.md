---
group:
  - notes
---
- Leverage unused EC2 capacity to provide huge discounts over On-Demand pricing
- Variable hourly price based on supply and demand

When launching Spot Instances, you have the ability to set a maximum price that you’re willing to pay for the instance. If the Spot price ever exceeds your maximum price, or if Spot capacity is no longer available, the EC2 service will reclaim the instance through what is called a Spot Instance interruption. When this happens, your instance will terminate, stop, or hibernate based on the behavior you specified when creating your Spot request. Because demand for Spot Instances can fluctuate, there’s always a risk that your instances may be interrupted at any time.

Because of this, Spot instances are only suitable for applications that are resilient to interruptions, such as batch jobs or background processing of data.