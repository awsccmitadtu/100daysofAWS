# Advanced Features of Amazon S3

## Lifecycle Rules

An Amazon S3 Lifecycle configuration is an XML file consisting of predefined rules for actions on objects during their lifetime.

- **Transition Actions**: Define when objects transition from one storage class to another.
- **Expiration Actions**: Define when objects expire and are deleted.

Watch:
- [Understanding Amazon S3 Lifecycle Rules](https://www.youtube.com/watch?v=b18KlhIgmjQ)
- [Amazon S3 Lifecycle Transition Actions](https://www.youtube.com/watch?v=53eHNSpaMJI)

## Replication Rules

Amazon S3 offers automatic copying of objects across S3 buckets, and it involves:

- **Cross-Region Replication (CRR)**: Replicate your bucket to other regions for data stored in multiple regions.
  - Watch: [Cross-Region Replication in Amazon S3](https://www.youtube.com/watch?v=_6admeBN-lI)
- **Same-Region Replication (SRR)**: Automatic and asynchronous replication of newly uploaded S3 objects to a destination bucket in the same AWS Region.

## Bucket Security

- **AWS IAM Policies**: To manage AWS access, you set IAM policies and link them to IAM identities (users, groups of users, or roles) or AWS resources. IAM policies specify which actions are allowed or denied on which AWS resources.
  - Watch: [Understanding AWS IAM Policies for S3](https://www.youtube.com/watch?v=gWAwqY76JQs)
- **Bucket Policies**: Resource-based policies that grant access permissions to your Amazon S3 buckets and the objects in them. S3 bucket policies can allow or deny requests based on the elements in the policy.
- **Bucket Encryption**: All Amazon S3 buckets have encryption configured by default, and objects are automatically encrypted by using server-side encryption with Amazon S3 managed keys (SSE-S3). This encryption setting applies to all objects in your Amazon S3 buckets.
  - Watch: [Configuring Amazon S3 Bucket Security](https://www.youtube.com/watch?v=xFzJw6wJ8eY)
  - Watch: [Configuring Amazon S3 Object Ownership](https://www.youtube.com/watch?v=fYFmCtYkcdY)

## Amazon S3 Versioning

Versioning allows keeping multiple variants of an object in the same bucket, aiding in recovery from unintended user actions and application failures.
- Watch: [Configuring Amazon S3 Versioning](https://www.youtube.com/watch?v=FVgui-wVPZE)

## Amazon S3 Transfer Acceleration

Amazon S3 Transfer Acceleration enables fast, easy, and secure transfers of files over long distances between your client and an S3 bucket. Transfer Acceleration takes advantage of Amazon CloudFront’s globally distributed edge locations.
Watch:
- [Understanding Amazon S3 Transfer Acceleration](https://www.youtube.com/watch?v=FVgui-wVPZE)
- [Configuring Amazon S3 Transfer Acceleration](https://www.youtube.com/watch?v=eyMAFVlkk2o&pp=ygUhZGF0YSB0cmFuc2ZlciBhY2NlbGVyYXRpb24gczMgbGFi)

## Additional Documentation

- [Amazon S3 Object Lifecycle Management](https://docs.aws.amazon.com/AmazonS3/latest/userguide/object-lifecycle-mgmt.html)
- [Disabling Replication in Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/disable-replication.html)
- [Amazon S3 Versioning Documentation](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Versioning.html)
- [Amazon S3 Transfer Acceleration](https://aws.amazon.com/s3/transfer-acceleration/)
