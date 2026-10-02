# Federation

## Understanding the Challenge

Let’s assume there are 500 users within an organization. Your organization are using 
3 services :

● AWS ( Infrastructure )
● Jenkins ( CI / CD )
● HR Activator  ( Payroll )

You have been assigned role to give users access to all 3 services.

<div align="center">
<img src="images/image1.png"  width="50%">
</div>

## Storing Users Centrally

<div align="center">
<img src="images/image2.png"  width="50%">
</div>

## Central Users

There are various solutions available which can store users centrally :

● Microsoft Active Directory

● RedHat Identity Management / freeIPA

<div align="center">
<img src="images/image3.png"  width="50%">
</div>

## Basics of Federation - AWS Perspective

- Federation allows external identities ( Federated Users ) to have secure access in your 

- AWS account without having to create any IAM users.

## Basic Workflow

<div align="center">
<img src="images/image4.png"  width="50%">
</div>

## Understanding Identity Broker

Identity Broker :

It is an intermediate service which connects multiple providers.

## Steps to Remember

● User logs in with username & Password.

● This credentials are given to the Identity Broker.

●  Identity Broker validates it against the AD.

●  If credentials are valid, Broker will contact the STS token service.

●  STS will share the following 4 things :

                   Access Key + Secret Key + Token + Duration

● User can now use to login to AWS Console or CLI.


<div align="center">
<img src="images/image5.png"  width="50%">
</div>


## Notations to Remember
Identities :   Users 

 Identity Broker : 

- It is a middleware that takes the users from point A & help connect them to 
point B.

Identity Store :

- Place where users are present. Eg : AD, IPA, Facebook etc.