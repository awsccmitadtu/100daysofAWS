# Deep Dive into S3

## Introduction to Storage

Computers use data to complete tasks, which must be stored to be accessed. It can be internal storage, servers, or servers in the cloud.

### Difference between On-premises storage and cloud storage

#### On-premises Storage

1. The server is hosted within your organisation’s infrastructure and might be physically onsite.
2. Your company controls, administers, and maintains the server.
3. Data and other information are shared between computers through your local network.

#### Cloud Storage

1. An outside service provider like AWS hosts your data.
2. The cloud provider procures, installs, and maintains all hardware, software, and other supporting infrastructure in its data centers.
3. You access and manage these services through the internet.

## Types of Cloud Storage

1. Block Storage
2. File Storage
3. Object Storage

 [Watch](https://www.youtube.com/watch?v=sswLpKeAoxs)

## Introduction to S3

Amazon S3 is an object storage service that you can use to collect, store, and analyze data in any amount from anywhere in the world.

[Watch](https://www.youtube.com/watch?v=_I14_sXHO8U)

## Core Concepts

1. **Bucket**: Buckets are permanent containers that hold objects.
2. **Object**: Objects are any piece of data stored within a bucket.

In Amazon S3 object storage, you can organize objects to imitate a hierarchy by using key name prefixes and delimiters. Prefixes and delimiters allow you to group similar items to help visually organize and easily retrieve your data.

[Watch](https://www.youtube.com/watch?v=tfU0JEZjcsg)

## Amazon S3 Durability and Availability

**Durability**: The measure of the average annual expected loss of objects. All Amazon S3 storage classes provide 11 9’s (99.999999999 %) of durability for objects over a given year.

**Availability**: The amount of time per year that an object stored in Amazon S3 is available for retrieval. All Amazon S3 storage classes have better than 99.9% availability.

### Storage Classes

[Watch](https://www.youtube.com/watch?v=wYclDu6GhkU)

1. Amazon S3 Standard
2. Amazon S3 Standard-Infrequent Access
3. Amazon S3 One Zone-Infrequent Access
4. Amazon S3 Glacier Flexible Retrieval
   [Watch](https://www.youtube.com/watch?v=gMzVi7Z8zBo)
5. Amazon S3 Deep Archive
6. Amazon S3 Intelligent Tiering
   [Watch](https://www.youtube.com/watch?v=6brzBokCYV0)

[Storage Classes Documentation](https://aws.amazon.com/s3/storage-classes/)

## Use Cases of Amazon S3

[Next Steps Documentation](https://docs.aws.amazon.com/AmazonS3/latest/userguide/getting-started-next-steps.html)

## Interfacing with Amazon S3

The three primary tools for interacting with buckets are the AWS Console, the AWS Command Line Interface (CLI), and using the AWS Software Development Kit (SDK).

## S3 Strong Data Consistency Model

Amazon S3 delivers strong read-after-write consistency for any storage request, without changes to performance or availability, without sacrificing regional isolation for applications, and at no additional cost. Any request for S3 storage is now strongly consistent.

[Amazon S3- Creating a bucket](https://www.youtube.com/watch?v=mDRoyPFJvlU)
