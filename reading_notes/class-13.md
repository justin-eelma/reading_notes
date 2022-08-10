# Cloud Virtualization with AWS

Virtualization is a packaged operating system that can run ontop of a host operation or virtualization layer. Traditional architecture, or no virtualization at all, would see the OS communicate directly with the hardware layer of a computer. Virtual architecture grabs a segment of the hardware which the virtualization layer is built on. In other words, you can have multiple virtual machines running at the same time within a host machine.

### Amazon Infrastructure as a Service

Amazon Elastic Compute Cloud (EC2) is a service that provides virtual servers based on the Xen hypervisor. The Xen hypervisor is a type 1 hypervisor, also known as a bare-metal hypervisor that runs directly on the physical machine without a host operating system (type 2 hypervisor requires a host). 

Amazon EC2 uses a virtual appliance called Amazon Machine Image (AMI), which is responsible for creating on-demand VM's within the cloud. You can launch multiple instances from a single AMI when you require multiple instances with the same configuration.

In conclusion, virtualizing is a cost effective way of running a enterprise, the elasticity of virtualizations have made it possible incorporate the appropriate amount resources for the task at hand. 
