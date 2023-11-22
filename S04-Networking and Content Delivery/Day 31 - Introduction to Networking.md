# Day 31: Introduction to Networking - Understanding Amazon VPC

Watch: [Introduction to Networking: Understanding Amazon VPC](https://www.youtube.com/watch?v=WmyiE27uKOo)

## Amazon VPC Overview
Amazon Virtual Private Cloud, or Amazon VPC, serves as a logically isolated virtual network dedicated to your AWS account. Within this environment, you can launch various AWS resources, including Amazon EC2 and Amazon RDS instances. Amazon VPC enables the hosting of multi-tier web applications, enforcement of security rules, and definition of connectivity between servers.

This virtual network, associated with a single AWS Region, establishes a boundary around AWS services and resources, governing their communication with each other and external networks like the internet. AWS supports hybrid cloud configurations, facilitating connections between an Amazon VPC and on-premises locations such as physical data centers.

## Types of Amazon VPCs

### Default VPC
- Automatically provided when setting up an AWS account.
- Includes a public subnet with internet access for each Availability Zone in the Region.
- Suitable for quick start-ups and launching public instances.
- It is advisable not to use or delete the default VPC.

Watch: [VPC](https://www.youtube.com/watch?v=QGgHig8ZHcg)

### Public and Private Subnets in VPC
Watch: [Public and Private Subnets in VPC](https://www.youtube.com/watch?v=ApGz8tpNLgo)

Read: [Understanding Public and Private Subnets in AWS VPC: Benefits and Use Cases](https://medium.com/@igor_y/understanding-public-and-private-subnets-in-aws-vpc-benefits-and-use-cases-8527c4d95c)

### Components of VPC
- Subnets
- Route Tables
- Network Gateways
- Network Access Control Lists (network ACLs)
- Security groups

Read: [AWS VPC Components](https://clouddeepdive.medium.com/aws-vpc-vpc-components-37fd536d8819)

### Steps of Deploying Amazon VPC
- Amazon VPCs reside in the AWS Cloud.
- An Amazon VPC is associated with a specific AWS Region.
- Each subnet is confined to a single Availability Zone.
- Certain AWS resources must be launched into an Amazon VPC.
- Internet gateways enable Amazon VPC resources to access the internet.
- Route tables govern traffic routing within Amazon VPCs.

Watch: [Deploying Amazon VPC](https://www.youtube.com/watch?v=horFs3Ipw_4)

## Use Cases of VPC
- Hosting multi-tier web applications.
- Defining network connectivity and restrictions between web servers, application servers, and databases.
- Implementing a three-tier architecture comprising presentation, logic, and data tiers.

Watch: [Deploy three-tier architecture](https://www.youtube.com/watch?v=sCBTeMd0Jj4)

## Additional Resources
- [FAQs](https://aws.amazon.com/vpc/faqs/)
- [Documentation](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)
