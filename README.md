# AWS Three-Tier-web-using-Terraform

## What it does 
This project automates the deployment of a 3-tier web application on AWS using Terraform. It eliminates the need to manually create VPCs, subnets, security groups, and EC2 instances, reducing setup time and errors.

## Introduction
This project demonstrates the use of **Infrastructure as Code (IaC)** to deploy a scalable web application architecture. It includes a **public web server** and a **private app server**, all running in a secure VPC. Terraform scripts are used to automate the provisioning of resources, making redeployment easy and repeatable.

## Architecture Diagram
<img width="1080" height="696" alt="3-tier drawio" src="https://github.com/user-attachments/assets/9c330c56-b282-42a8-ba6a-59234a37ab06" />
<img width="1366" height="768" alt="2025-10-03 (1)" src="https://github.com/user-attachments/assets/899b8c8c-4245-4906-a743-8e4ae926a2a9" />
<img width="1366" height="768" alt="2025-10-03" src="https://github.com/user-attachments/assets/9bd819f8-7242-4bd8-aa08-0bee587c4d78" />
<img width="1366" height="768" alt="2025-10-03 (4)" src="https://github.com/user-attachments/assets/47a66a91-9b74-46eb-801e-233411679e07" />
<img width="1366" height="768" alt="2025-10-03 (3)" src="https://github.com/user-attachments/assets/ec2e9338-4031-43be-9ab5-79740caf446b" />

## User Instructions
1. Ensure you have an **AWS account** and an IAM user with **programmatic access**.  
2. Install **Terraform** and **AWS CLI** on your local machine.  
3. Create project folder for your project
4. Attach commands to each folder
5. Configure AWS CLI
6. Initialize Terraform
7. Plan and apply the deployment
8. Access the web server via the public IP provided

## My Instructions
1. Ensure your key pair name matches the AWS key you created.
2. Ensure key pair is in the same region as configured in Terraform
3. Wait a few minutes for AWS to assign a public DNS to the web server.

   ## My Issues
1. AMI IDs are region-specific and may need updating.
2. Currently, the app server does not host a real backend service; it is configured for demonstration.
3. Public DNS may not appear immediately after deployment. Use the public IP in the meantime.

   ## Hire Me
   Email: suaramaryam@gmail.com
   
   LinkedIN: www.linkedin.com/in/maryam-suara
