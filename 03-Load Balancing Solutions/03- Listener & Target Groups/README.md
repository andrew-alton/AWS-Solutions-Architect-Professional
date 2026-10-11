# Listener & Target Groups

## Understanding Listeners
A listener is a process that checks for connection requests, using the protocol and port that you 
configure.

<div align="center">
<img src="images/image1.png"  width="50%">
</div>


## Listener Rules
Each listener has a rule based on which an action is taken based on a request.

<div align="center">
<img src="images/image2.png"  width="50%">
</div>

## Listener Rule Actions

If a request matches a specific rule, what action you want to perform on that request is 
determined in the Rule Actions.

<div align="center">
<img src="images/image3.png"  width="50%">
</div>

</br>

<div align="center">
<img src="images/image4.png"  width="50%">
</div>

## Understanding Target Groups
Target group is used to route requests to one or more registered targets. 
These targets can be EC2 instances, Lambda Functions, and others.

<div align="center">
<img src="images/image5.png"  width="50%">
</div>

## Overall Workflow

<div align="center">
<img src="images/image6.png"  width="50%">
</div>


