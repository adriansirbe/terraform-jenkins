# terraform-aws-resources
### A repository for creating/deleting AWS resources with terraform.
### This project is for personal use.

terraform version = v0.12.28

### This repository creates the following resources:
### - s3 bucket for terraform state
### - dynamodb table for terraform state lock
### - security group for jenkins
### - subnet for infrstructure on which jenkins will be attached
### - vpc for infrastructure on which jenkins will be attached
### - ec2 for jenkins with user_data template file which makes jenkins up and running on port 8080 when a ec2 instance spins up
### - s3 bucket for web application
### - cloudfront distribution which uses the s3 bucket for web application as origin
