# S3 Bucket Policy

## Granting Permission for S3 Resource
  
There are two primary ways in which a permission to a S3 resource is granted.

<div align="center">
<img src="images/image1.png"  width="50%">
</div>

## Use-Case 1: IAM User Needs Access to S3 Bucket

IAM User Named Bob needs Full Access to S3 Bucket.

<div align="center">
<img src="images/image2.png"  width="50%">
</div>

## Wider Scope of S3 Bucket

Files within the S3 bucket can have scope beyond the IAM entity.

Organization can host entire websites in S3 Bucket.

S3 Buckets can even be used to host central files for download.

<div align="center">
<img src="images/image3.png"  width="50%">
</div>

## S3 Bucket Policy

A bucket policy is a resource-based AWS IAM policy associated with the S3 Bucket to control 
access permissions for the bucket and the objects in it .

<div align="center">
<img src="images/image4.png"  width="50%">
</div>