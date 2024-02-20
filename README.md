# assignment

 1. Improvements can be done to this model
 2. NAT gateway can be deployed in two  different AZ  to support High availablity
 3. EC2 instances spin up in different AZ to maintain high Availablity
 4. We can add a certificate validation code to validate cert from Route 53
 5. The microservice can be deployed on ECS task defination as a service as EC2 are more reliant to failure 

Security prospective :

The LB can be made private and we can use a IGW to take request and attach a VPC link to make our request private , rather exposing on public 
