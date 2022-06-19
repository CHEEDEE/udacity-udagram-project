# Project Title - Deploy a high-availability web app using CloudFormation

This repo contains Cloud Formation Templates to deploy infrastructure shown below: a highly available web site on AWS

![Udagram app](https://user-images.githubusercontent.com/91762320/174493629-fb30e8ac-c65b-420f-8b44-e1bcb80a2deb.jpeg)

Network-infrastructure.yml && network-parameters.json contains template and parameters to deploy the networking components of the infrastructure, such as VPC, Internet Gateway, Private and Public Subnets, etc.
Server-Infrastructure && server-parameters.json contains template and parameters to deploy the server components, such as the Application load balancer, Autoscaling group and web servers.
The website is accessible via the Application load balancer created

How to deploy stack
To deploy any of the templates, use the command below upon successfully logging in to the aws cli
