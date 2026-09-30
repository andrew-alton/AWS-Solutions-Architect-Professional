# Cross Account S3 Access

  
There are many requirements where logs across all AWS accounts need to be stored in a central 
account.

These logs can include, CloudTrail, CloudWatch, Application Logs, and others.

<div align="center">
<img src="images/image1.png"  width="50%">
</div>

## Creating Bucket Policy

The recommended approach is to add a Bucket Policy in the Central S3 bucket and allow the 
Account B to push the logs

<div align="center">
<img src="images/image2.png"  width="50%">
</div>

## Bucket Policy Example - Central S3 Account

<div align="center">
<img src="images/image3.png"  width="50%">
</div>

## Part 2- Permission on Account B Side

The resource in the Account B also needs to have permission to push the logs to Central 
Account S3 Bucket.

<div align="center">
<img src="images/image4.png"  width="50%">
</div>

## IAM Policy - Account B 


<div align="center">
<img src="images/image5.png"  width="50%">
</div>