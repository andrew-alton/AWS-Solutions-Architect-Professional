# Organizational Units (OUs) in AWS Organizations

## Setting the Base

Large organizations may manage hundreds of AWS accounts.
Applying policies to accounts — such as those used for development — can be complex
and difficult to manage if not grouped together.
Example: Attach “DenyS3” SCP to all Development Accounts.

<div align="center">
<img src="images/image1.png" alt="IAM Policies" width="600">
</div>

## Introducing Organizational Units

An Organizational Unit (OU) allows customers to to group AWS accounts.
You can apply policies at OU level.

<div align="center">
<img src="images/image2.png" alt="IAM Policies" width="600">
</div>

## Point to Note

You can create multiple OUs within a single organization, and you can create
OUs within other OUs.

<div align="center">
<img src="images/image2.png" alt="IAM Policies" width="600">
</div>
