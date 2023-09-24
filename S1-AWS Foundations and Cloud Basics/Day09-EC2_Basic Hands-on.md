# AWS EC2 Instance Setup Guide

This guide will walk you through the steps to launch and configure an Amazon Elastic Compute Cloud (Amazon EC2) instance in AWS. Amazon EC2 provides resizable computing capacity in the cloud, making it a versatile choice for various applications.

## Prerequisites

Before you begin, make sure you have the following:

- An AWS account.
- AWS Management Console access.
- Basic knowledge of AWS services.

[Refer this Article for Hands-on and Proper Project](https://glitchyhitchy.medium.com/hands-on-amazon-elastic-compute-cloud-ec2-3b90563cbd02)

## Steps

### Step 1: Log into AWS Management Console

Log in to your AWS account via the [AWS Management Console](https://aws.amazon.com/console/).

### Step 2: Create an Amazon Linux Instance from an Amazon Linux AMI

1. Navigate to the EC2 service.
2. Click "Launch Instances."
3. Select an Amazon Machine Image (AMI), e.g., "Amazon Linux 2 AMI (HVM), SSD Volume Type."

### Step 3: Choose an Instance Type

Select the desired instance type, such as "t2.micro" for a basic setup.

### Step 4: Configure Instance Details

Keep the default settings and proceed.

### Step 5: Add Tags

Add a tag to your instance for easy identification, e.g., `Name: MyEC2Server`.

### Step 6: Configure Security Group

1. Create a new security group.
2. Define rules for SSH (custom or anywhere), HTTP, and HTTPS access.

### Step 7: Review Instance Launch

1. Review your configuration.
2. Launch the instance.
3. Create or select a key pair for secure access (e.g., "ec2.pem").
4. Download the key pair for SSH access.
5. Launch the instance.

### Step 8: View Instances

Monitor the instance status in the AWS Management Console until it shows "Running."

### Step 9: SSH into Your Instance

Use the downloaded key pair to SSH into your EC2 instance.

### Step 10: Configure EC2 Instance as a Web Server

Install and configure a web server (e.g., Apache, Nginx) on your EC2 instance.

### Step 11: Create and Publish a Sample `test.html` File

Create a sample HTML file (e.g., "test.html") and place it in the web server's document root directory.

### Step 12: Test the Page

Access the HTML file using the public IP address of your EC2 instance to ensure the web server is working correctly.

## Conclusion

This guide provides a step-by-step process for launching and configuring an EC2 instance in AWS. You can use this virtual machine for various computing tasks, including hosting websites, running applications, and more.

Enjoy your AWS EC2 instance!
