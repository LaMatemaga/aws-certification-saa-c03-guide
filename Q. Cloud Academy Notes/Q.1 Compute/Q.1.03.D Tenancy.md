---
group:
  - notes
---
Now let’s discuss [[Amazon EC2]] tenancy and how it relates to the underlying [[host]], or [[physical server]] within an AWS [[data center]] where your EC2 instance will reside.
## Shared Tenancy

When you launch a new EC2 instance, it will run with [[shared tenancy]] by default.
- Instances run on available hosts with resources required for your selected instance type
- Other users may have instances running on the same host
- Security mechanisms prevent different customers' instances from accessing each other on the same host
## Dedicated Tenancy

There may be instances where your workloads must run on dedicated hardware due to internal security policies or external compliance controls. In these cases, you’ll want to use [[dedicated tenancy]].

Dedicated tenancy includes both Dedicated Instances and Dedicated Hosts.
- **Dedicated Instances**
	- Dedicated instances are hosted on hardware that no other customers can access.
	- They incur additional charges because no other customers may run EC2 instances on the same hardware, and so there will likely be unused capacity remaining.
	- However, this hardware can be shared by other resources you have running in your own account.
- **Dedicated Hosts**
	- However, Dedicated Hosts offer additional visibility and control around how you can place your instances on the physical host.
	- They also allow you to use your existing per-socket, per-core, or per-VM software licenses that may need to be tied to a specific machine.
A Dedicated Host is effectively the same as a Dedicated Instance. But if you don't need to address any specific licensing, compliance, or security issues that would require dedicated tenancy, then I’d recommend using the default shared tenancy to reduce your overall costs.