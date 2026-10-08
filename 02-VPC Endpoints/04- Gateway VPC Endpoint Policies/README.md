# Gateway VPC Endpoint Policies


## Understanding the Challenge
By default, Gateway VPC Endpoint will allow EC2 instances to connect to ALL 
the destination resources (S3 Buckets) [provided permissions are present]

<div align="center">
<img src="images/image1.png"  width="50%">
</div>

## Default Policy of Gateway Endpoint
The access to ALL S3 buckets is allowed because of the Default Gateway 
Endpoint Policy that gets associated.

<div align="center">
<img src="images/image2.png"  width="50%">
</div>


## Customization on the Policy
Based on requirements, we can customize the Gateway VPC Endpoint policy to 
allow access to only certain S3 buckets.

<div align="center">
<img src="images/image3.png"  width="50%">
</div>

## Point to Remember - Policy Decision
There are multiple places in which permission can be DENIED for a resource.
IAM Policy, VPC Endpoint Policy, S3 Bucket Policy.
ONE Deny = Total Deny of Request.

<div align="center">
<img src="images/image4.png"  width="50%">
</div>