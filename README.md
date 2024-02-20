# assignment

> Improvements can be done to this model
> NAT gateway can be deployed in two  different AZ  to support High availablity
> EC2 instances spin up in different AZ to maintain high Availablity
> We can add a certificate validation code to validate cert from Route 53
> The microservice can be deployed on ECS task defination as a service as EC2 are more reliant to failure 

Security prospective :

The LB can be made private and we can use a IGW to take request and attach a VPC link to make our request private , rather exposing on public 
