# AWS-VPC-PROJECT

## The Main objective of this project is Accessing the application in EC2 using Bastion Host/ Jump Server

Mainly focusing on : 

> Auto scaling 

> load balancer

> Route53

> Bastion Host/ Jump Server

In this project to increase the resiliency,I am deploying the **servers in two availability zones** and also using **auto scaling** and **load balancer**.
To increase the **security** servers are deployed in **private subnets** and **servers** receives the requests through the **load balancer**. servers can connect to the internet by using **NAT gateway** and
to improve the resiliency I will deploy the **NAT gateway** in both **availability Zones**. Both the servers are accessed using the **Bastion Host**. 
