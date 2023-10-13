# Amazon Elastic Block Store (EBS) Overview

This repository provides an overview and essential information about Amazon Elastic Block Store (EBS) on Amazon Web Services (AWS). EBS is a scalable and high-performance block storage service designed for providing persistent storage for EC2 (Elastic Compute Cloud) instances.

## Key Points

### 1. Block Storage

EBS offers block-level storage, allowing you to create and attach storage volumes to your EC2 instances. These volumes function similarly to physical hard drives.

### 2. Scalability

EBS volumes can be easily scaled up or down to accommodate changing storage requirements for your applications. You can increase the size or change the volume type without incurring downtime.

### 3. Persistence

Data stored on EBS volumes is highly durable and persistent. Even if the associated EC2 instance is stopped or terminated, the data on the EBS volumes remains intact.

### 4. Snapshotting

EBS enables the creation of point-in-time snapshots of your volumes. Snapshots are incremental backups stored in Amazon S3. They can be used for data backup, disaster recovery, and creating new volumes.

### 5. Performance Tiers

EBS offers different volume types optimized for various workloads, including:
- General Purpose (SSD)
- Provisioned IOPS (SSD)
- Throughput Optimized HDD
- Cold HDD
- And more, each with specific characteristics and performance attributes.

### 6. Encryption

EBS supports data-at-rest encryption, enhancing data security. You can utilize the AWS Key Management Service (KMS) to manage encryption keys.

## Usage

This repository provides a general overview of EBS. For detailed information and resources, refer to AWS's official documentation and guides.

## Contributing

If you'd like to contribute to this repository or have suggestions for improvements, please feel free to create an issue or submit a pull request.

## Video Reference

For a more in-depth understanding of Amazon Elastic Block Store, you can watch this informative video on YouTube:

[Amazon EBS Explained](https://youtu.be/udQQQrnr6fY?si=qG6D2gnUd2Zyinki)

This video covers various aspects of Amazon EBS and can be a valuable visual resource.

