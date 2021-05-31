# Amazon S3

#### Amazon Simple Storage Service (Amazon S3) is a scalable, high-speed, web-based cloud storage service. The service is designed for online backup and archiving of data and applications on Amazon Web Services.

#### AWS S3 Terminology:

#### Bucket: Data, in S3, is stored in containers called buckets.

#### Each bucket will have its own set of policies and configuration. This enables users to have more control over their data.

#### Bucket Names must be unique.

#### Can be thought of as a parent folder of data.

#### There is a limit of 100 buckets per AWS accounts. But it can be increased if requested from AWS support.

#### Bucket Owner: The person or organisation that owns a particular bucket is its bucket owner.

#### Import/Export Station: A machine that uploads or downloads data to/from S3.

#### Key: Key, in S3, is a unique identifier for an object in a bucket. For example in a bucket ‘ABC’ your GFG.java file is stored at javaPrograms/GFG.java then ‘javaPrograms/GFG.java’ is your object key for GFG.java.

#### It is important to note that ‘bucketName+key’ is unique for all objects.

#### This also means that there can be only one object for a key in a bucket. If you upload 2 files with the same key. The file uploaded latest will overwrite the previously contained file.

### Features of AWS S3:

#### Durability: AWS claims Amazon S3 to have a 99.999999999% of durability (11 9’s). This means the possibility of losing your data stored on S3 is one in a billion.

#### Availability: AWS ensures that the up-time of AWS S3 is 99.99% for standard access.

#### Server-Side-Encryption (SSE): AWS S3 supports three types of SSE models:

#### SSE-S3: AWS S3 manages encryption keys.

#### SSE-C: The customer manages encryption keys.

#### SSE-KMS: The AWS Key Management Service (KMS) manages the encryption keys.
