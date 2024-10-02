# Project Overview

This Terraform project is designed to create an infrastructure with multiple EC2 instances and two load balancers, as illustrated in the provided diagram. 


![Project Architecture](screenshots/project.png)

#### The infrastructure consists of :

1. A Virtual Private Cloud (VPC) with public and private subnets.
1. EC2 instances configured as web servers in the private subnets.
3. A proxy server in the public subnets that routes traffic to the private web servers..
4. Two load balancers:
-  Public load balancer:  that forwards traffic to the proxy server.
-  Private load balancer :  that forwards traffic to the backend EC2 web servers.

#### This project utilizes AWS services, including EC2, Elastic Load Balancers (ELB), and S3 for storing Terraform state files.

## S3 : 
![Project Architecture](screenshots/dynamodb.PNG)

![image](https://github.com/user-attachments/assets/f3e6b71b-7ef8-436b-9a94-9eb392d45318)
## VPC : 
![image](https://github.com/AyaOmer/Secure-Cloud-Architecture_using-Terrraform/blob/master/screenshots/vpc.PNG)
## Subnets : 
![image](https://github.com/AyaOmer/Secure-Cloud-Architecture_using-Terrraform/blob/master/screenshots/subnet.PNG)
##  Internet GateWay : 
![image](https://github.com/AyaOmer/Secure-Cloud-Architecture_using-Terrraform/blob/master/screenshots/internet%20gateway.PNG)
## EC2 Instances:
![image](https://github.com/AyaOmer/Secure-Cloud-Architecture_using-Terrraform/blob/master/screenshots/ec2.PNG)
## Load Balancers:
![image](https://github.com/AyaOmer/Secure-Cloud-Architecture_using-Terrraform/blob/master/screenshots/loadbalancer.PNG)

## SSH to Bastion Host:
![image](https://github.com/AyaOmer/Secure-Cloud-Architecture_using-Terrraform/blob/master/screenshots/ssh%20to%20public%20ec2.PNG)

