#  Important Concepts - AWS Service Catalog

## Important Concept - Product and Portfolio

A Product is a blueprint for deploying AWS resources. It is typically a 
CloudFormation template (or Terraform, etc.) that defines the infrastructure you 
want to provision.

A Portfolio is a collection of products, plus configuration related to access 
permissions, constraints, sharing, tags.

<div align="center">
<img src="images/image1.png"  width="50%">
</div>

## End User Workflow

1. End user will be able to see list of Products they have access to.
2. Based on requirement, end user can launch the product.

<div align="center">
<img src="images/image2.png"  width="50%">
</div>

## Constraints

We can apply constraints to control the rules that are applied to a product in a 
specific portfolio when the end users launches it.

<div align="center">
<img src="images/image3.png"  width="50%">
</div>

## Reference Screenshot - Portfolio 
The screenshot displays Portfolio where Alice user has access to the associated 
products.

<div align="center">
<img src="images/image4.png"  width="50%">
</div>

## Reference Screenshot - Portfolio 

The screenshot displays two products based on type of 
CLOUDFORMATION_TEMPLATE

<div align="center">
<img src="images/image5.png"  width="50%">
</div>