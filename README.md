# iac-with-terraform

## Description

Provisioning resources on AWS using Terraform.
- Provisioned the following resources: VPC, Public Subnet, Internet Gateway, Route Table, Security Groups, EC2 Instance.
- Used a shell script to install docker and run nginx container on the EC2 Instance.

## Getting Started

### Dependencies

* AWS
* Terraform
* AWS CLI

### Executing program

* Have an AWS Account and necessary permissions.
* Configure with AWS account using aws cli.
* Install Terraform.
* Execute main.tf file.
* The nginx server starts on port 8080.
```
terraform init
terraform apply
```
