# Network

## VPC
Amazon Virtual Private Cloud (Amazon VPC) lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways. You can use both IPv4 and IPv6 in your VPC for secure and easy access to resources and applications.

#### Template parameters

* **CIDR Block**: IP range in CIDR notation (10.10.0.0/16)

#### Template content
* 1 Private subnets in 1 availability zone.
* 1 Public subnets in 1 availability zone.
* 1 Internet gateway and its attachment.
* 1 Nat gateways and its attachment.
*   Route tables and associations.
* 1 Elastic IPs for the NAT gateway.
* Necessary access control list for each subnet.

![VPC Diagram](../images/VPC.png)
