# Repository Index
## Overview
Welcome to the Devops_Projects! This repository contains various projects, scripts, and documentation organized into distinct directories.
That were done by me while pursuing my DevOps Course.
Each folder serves a specific purpose, whether it's related to infrastructure as code, CI/CD pipelines, or automation scripts.

This `README.md` provides an index of all key components of the repository to help you navigate and understand the contents.

> IMPORTANT NOTE


> We have a product called V-Profile. It is a website written in Java. Consists of multiple services.
> We will be deploying this product on virtual machines and cloud platforms using differnt services.
> The same code or the product has been used for all the projects but with the different approaches based on the differnt use cases.

> NOTE: The code is not written by me i have taken code from my instructor who has designed this code for the differnet scenarios.
> Each folder contains the steps and the code related to it.


## Directory Structure

The repository is organized as follows:

```plaintext
├── Project-01/
├── Project-02/
├── Project-03/
├── Project-04/
├── Project-05/
├── Project-06/
├── Project-07/
└── LICENSE
└── README.md
```

## Project-01 
## (V-Profile Project MANUAL and AUTOMATED)
In this project, we are going to set up a web application stack. The name of the project is V Profile Project set up local.
In this project, we will be setting a multi-tier web application stack. The set up will be locally on your laptop or on your desktop.
There are two reasons why we are doing this project.

- The first reason is this project is going to set up a baseline for our upcoming projects. 
We are going to do a lot of projects like we're going to deploy a stack on a.
We're going to refactor it. We're going to containerized our applications. 
We're going to deploy the projects on Kubernetes cluster and many more things to do. 
All the upcoming projects you need to understand, v profile project first, and for that we are doing a setup on your on our local machine.
- The second reason of doing this project is so you can set up your own lab locally. 
If you have any project you're working in, any project, you can set up that entire stack locally and do all your R&D.

## Project-02 
## (V-Profile Project on CONTAINERS)
In this Project, we will see how to run our Vprofile application on containers. Now this project is more of a trailer of what is coming next in Docker.
Everything is ready made over here. We just need to bring up the VM and run our Vprofile containers on it.
In this project, we will see how these things will run on the container together. We are going to run this entire setup on a virtual machine.
So in the virtual machine, you will have all these containers running and we will access it. And we bring up the containers using the docker compose file.

## Project-03
## (MICROSERVICES Project on CONTAINERS)
In this Project we will deploy a microservice application.
The name is EMart. This application was designed by using microservice architecture.
In the front end you have an API Gateway created with nginx and this listens at three endpoints, root, slash api, slash web api.
When the user access the URL of the website, it'll be redirected to root, which is an app written in Angular. This will give the front end also called client app. And this will in turn connect to slash api, which will be served by an application Mart api NodeJS. And it also needs MongoDB Database. And the MongoDB Database we are going to deploy as a container, but it could be an independent service running from a server or from any other endpoint.This application also has slash web api, which connects to an application, Books api, which is written in Java and this also needs a database, a MySQL Database.

## Project-04 
## (AWS Cloud Project set-up | LIFT & SHIFT)
This is an AWS cloud computing project.
The name of this project is lift and shift application workload, and we're going to lift our application, the vprofile and shift it on AWS cloud.
In this project, we are going to host and run it on AWS cloud for production. And we're going to use a lift and shift strategy for this.
After going through this project, we will learn how to run application workload on AWS cloud by using lift and shift strategy.
We're using AWS cloud computing and the services that we are going to use In this project are: 
- Starting with ec2 instances. Ec2 instances will be our VMs for Tomcat, rabbitmq, Memcache and mysql servers.
- We will be also using elastic load balancer, which will be replacement of our engine service.
- Will be using auto scaling service, which will automatically scale out and scale in our ec2 instances, which will automatically control our resources and also our cost.
- For storage, we will be using S3 or EFS
- so and also Route 53 for a private DNS service.
- Along with these we will be using few more services like IAM, ACM, EBS etc

## Project-05
## (Re-Architecting Web App on AWS Cloud [PAAS & SAASS])
So from our previous project, we have seen, we deployed the vprofile application stack on our local machine and also on AWS Cloud.
From our previous project, we already know how to host our Web application stack on AWS Cloud.And we used lift and shift strategy.
In this project, we will re architecture or refactor our services, this strategy is called re architecture or refactoring.
We're using AWS cloud computing and the services that we are going to use In this project are: 

Front-end
- Beanstalk for app server, LB, Scaling
- S3/EFS for storing the artifacts
- Cloudwatch for monitoring

Back-end
- RDS Instnace for DataBase [PAAS]
- Elastic Cache 
- Active MQ
- Route53 for DNS
- Cloudfront for content delivery network

## Project-06 
## (3-Tier Infrastructure using Terraform)
This Project defines a scalable and modular 3-tier infrastructure using Terraform. 
The architecture is designed to deploy applications with a clear separation of concerns across three layers:
- Presentation Layer (Frontend)
- Application Layer (Backend)
- Data Layer (Database)
  
The folder contains the Terraform code that can be used for designing a infrastructure for a web application.

## Project-07
## (AWS CI/CD Project)
In this project, we are going to use AWS services to fetch our code, build it and deploy it on AWS Elastic Beanstalk.
As you may have seen Jenkins CI CD pipeline, Same way we are going to create a code pipeline, but we are going to use AWS services for that.
We are going to migrate it from GitHub to Bitbucket.Then we are going to use AWS Code Build service, which is going to fetch the source code from Bitbucket
and deploy it on Beanstalk.

For the code Repository we are using 
- Bitbucket
  
We're using AWS cloud computing and the services that we are going to use In this project are: 
- Elastic Beanstalk
- RDS
- CodePipeline
- CodeBuild
- Cloud watch
  
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



