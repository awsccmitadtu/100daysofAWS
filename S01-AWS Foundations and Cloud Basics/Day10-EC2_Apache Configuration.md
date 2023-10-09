# AWS EC2 and Apache Web Server Configuration Guide

Welcome to the AWS EC2 and Apache Web Server Configuration Guide! This guide will walk you through the process of setting up an Amazon Web Services (AWS) Elastic Compute Cloud (EC2) instance and configuring an Apache web server. Whether you're new to AWS or looking to expand your skills, this guide has you covered with step-by-step instructions and advanced CLI options.


## Project Overview

This guide includes a hands-on project with three main objectives:

### Objective #1: Create an EC2 Instance

1. Sign in to your AWS account.
2. Launch an EC2 instance with a free-tier eligible OS (Operating System).
3. Configure security groups to allow incoming traffic on port 80 (HTTP) and port 22 (SSH).

### Objective #2: Configure Apache Using User Data

1. Use user data to create a script that updates packages, installs Apache, and starts the Apache service.
2. Launch an EC2 instance with this user data script, either via the AWS Management Console or AWS CLI.

### Objective #3: Verify Apache Installation

1. Access the public IP address of your EC2 instance in a web browser.
2. Confirm that Apache web server is installed and running by seeing the Apache welcome page.


[Refer this Article for Hands-on and Proper Project](https://medium.com/@stephanietabares/hands-on-experience-with-aws-ec2-and-apache-web-server-configuration-6686a0efb6c4)

## Advanced Usage

For those who prefer the AWS Command Line Interface (CLI), this guide also provides advanced steps:

### Advanced Objective #1: Create an EC2 Instance via AWS CLI

1. Install and configure AWS CLI on your local machine.
2. Locate the AMI ID and create a security group associated with your default VPC.
3. Ensure ports 22 and 80 are open in your security group.
4. Use AWS CLI to launch an EC2 instance with your chosen AMI and security group.

### Advanced Objective #2: Configure Apache Using User Data via AWS CLI

1. Create a user data script with the necessary commands for Apache installation.
2. Launch an EC2 instance via AWS CLI, using the user data script for configuration.

### Advanced Objective #3: Verify Apache Installation via AWS CLI

1. Check the public IP address of your EC2 instance using AWS CLI.
2. Access the public IP in your web browser to ensure Apache is running.

## Conclusion

This guide simplifies the process of configuring an AWS EC2 instance and Apache web server. It's designed to help beginners gain practical experience, and for those interested in AWS CLI, it offers advanced command-line options. By following these steps, you'll be able to confidently deploy and configure web servers on AWS EC2 instances.

Happy configuring!
