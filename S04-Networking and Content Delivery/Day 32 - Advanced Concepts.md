# Day 32: Advanced Concepts

## Elastic IP Address:

When creating a VPC, each instance within that VPC is automatically assigned a private IP address. Additionally, you have the option to request a public IP address during instance creation by modifying the subnet's auto-assign public IP address properties.

An Elastic IP address is a static public IPv4 address designed for dynamic cloud computing. When associated with an EC2 instance, it replaces the default public IP address. This feature allows masking instance failures by rapidly remapping the address to another instance within the VPC, remaining unchanged during events like stopping or restarting the instance.

Watch: [Elastic IP Address](https://www.youtube.com/watch?v=wfyClQKSf9Q)

## AWS VPN:

By default, instances within a VPC cannot communicate with a remote network. To establish connectivity between your VPC and a remote network through a virtual private network (VPN) connection, follow these steps:

- Create a virtual private gateway and attach it to your VPC.
- Define the configuration of the customer gateway, which provides information about your VPN device.
- Create a custom route table pointing traffic to the VPN gateway and update security group rules.
- Establish an AWS site-to-site VPN connection to link the two systems.

Watch: [AWS VPN](https://www.youtube.com/watch?v=7tTrN8WXMlg)

## VPC Endpoints:

- **Interface VPC Endpoints:**
  AWS PrivateLink enables private connectivity between VPCs, AWS services, and on-premises networks without exposing traffic to the public internet. Create interface VPC endpoints to connect to services powered by AWS PrivateLink. Charges apply for creating and using interface endpoints.

- **Gateway Endpoints:**
  Gateway endpoints offer reliable connectivity to Amazon S3 and Amazon DynamoDB without requiring an internet gateway or NAT device for your VPC. They do not enable AWS PrivateLink, and there's no additional charge for using gateway endpoints.

Watch: [VPC Endpoints](https://www.youtube.com/watch?v=6QS9YFGu5WI)

## VPC Peering:

A VPC peering connection establishes a networking connection between two VPCs, allowing private routing of traffic between them. Instances in either VPC can communicate as if they were part of the same network. You can create VPC peering connections between your VPCs, with VPCs in other AWS accounts, or even across different AWS Regions.

To set up a peering connection, create rules in your route tables to permit communication between VPCs through the peering resource. For example, in the route table for VPC A, set the destination as the IP address of VPC B with the target being the peering resource ID, and vice versa for VPC B.

Watch: [VPC Peering](https://www.youtube.com/watch?v=ZFe70EZqU18&pp=ygUPdnBjIHBlZXJpbmcgYXdz)
