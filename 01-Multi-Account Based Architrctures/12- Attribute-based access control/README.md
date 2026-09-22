# Attribute-based access control

## Basics of RBAC

Role-based access control (RBAC) restricts access based on a person's role 
within an organization.

In IAM, you implement RBAC by creating different policies for different job 
functions.

<div align="center">
<img src="images/image1.png"  width="50%">
</div>

## Understanding the Challenge

DevOps Team has access to Red and Green Environment;

<div align="center">
<img src="images/image2.png"  width="50%">
</div>


## Possible Approach of Separation

Red   -->   Env DevOps only has access to Red Environment
Green -->   Env DevOps only has access to Green Environment

<div align="center">
<img src="images/image3.png"  width="50%">
</div>

## Basics of Attributes

Attributes are key-value pairs.

In AWS, these attributes are called tags.

<div align="center">
<img src="images/image4.png"  width="50%">
</div>

## Scalable Permission Model based on Attributes

<div align="center">
<img src="images/image5.png"  width="50%">
</div>

## Attributes for IAM User

You can use IAM tag key-value pairs to add custom attributes to an IAM user.

<div align="center">
<img src="images/image6.png"  width="50%">
</div>

## Attribute-Based Access Control

Attribute-based access control (ABAC) is an authorization strategy that defines 
permissions based on attributes.

<div align="center">
<img src="images/image7.png"  width="50%">
</div>

## Permissions Based on ABAC

This example shows an IAM policy that allows a principal to start or stop an 
Amazon EC2 instance when the instance's resource tag and the principal's tag 
have the same value for the tag key Team

<div align="center">
<img src="images/image8.png"  width="50%">
</div>

## Benefits of ABAC

ABAC requires fewer policies. Because you don't have to create different 
policies for different job functions, you create fewer policies. Those policies are 
easier to manage.

Permissions can easily be granted and revoked based on user’s tags.

You can even use attributes of users from corporate directory to allow / deny 
permissions to AWS resources.