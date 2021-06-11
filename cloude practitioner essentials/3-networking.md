# VPC Virtual Private Cloud

A VPC is a barrier around the infrastructure environment preventing unauthorized traffic.

The **VPG** Virtual Private Gateway and the **IGW** Internet Gateway are the doors that allows traffic into and out of the VPC.

Within a VPC there can be both public and private subnets

# Subnets and network access control

> **Subnets** have stateless packet filtering meaning packets are checked both ways

> **Security Groups** have stateful packet filtering meaning they remember the outgoing decision and automatically allow on the way back in

![Screenshot from 2021-06-11 11-34-34](https://user-images.githubusercontent.com/73107656/121673644-03fb0b80-caa9-11eb-91e2-014a2d5c3ef9.png)

# Global Networking

![Screenshot from 2021-06-11 11-38-01](https://user-images.githubusercontent.com/73107656/121674063-7ec42680-caa9-11eb-981b-53f741228011.png)

Amazon Route 53 is a DNS web service. It gives developers and businesses a reliable way to route end users to internet applications hosted in AWS.

Amazon Route 53 connects user requests to infrastructure running in AWS (such as Amazon EC2 instances and load balancers). It can route users to infrastructure outside of AWS.

Another feature of Route 53 is the ability to manage the DNS records for domain names. You can register new domain names directly in Route 53. You can also transfer DNS records for existing domain names managed by other domain registrars. This enables you to manage all of your domain names within a single location.
