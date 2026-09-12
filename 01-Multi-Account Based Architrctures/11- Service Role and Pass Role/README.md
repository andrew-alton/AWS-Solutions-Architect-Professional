# Service Role and Pass Role

## Overview of Service Roles
A Service Role is an IAM role that an AWS service assumes to perform actions 
on your behalf.

<div align="center">
<img src="images/image1.png"  width="50%">
</div>

## Overview of Pass Role

PassRole is an IAM permission that controls who can assign roles to AWS 
resources. 
It allows certain IAM principals to pass an existing role to an AWS service.

<div align="center">
<img src="images/image2.png"  width="50%">
</div>

## Reference Screenshot - IAM Policy for PassRole

<div align="center">
<img src="images/image3.png"  width="50%">
</div>

## Important Pointer
After a role is associated with a CloudFormation stack, any user who has 
permission to work with that stack can operate that stack, even if they do not 
have permission on the underlying resource.

<div align="center">
<img src="images/image4.png"  width="50%">
</div>