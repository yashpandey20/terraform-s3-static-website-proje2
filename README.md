# Hosting a Static Website on Amazon S3 Using Terraform

## Project Overview
This project demonstrates how to deploy and host a static website on Amazon S3 using Infrastructure as Code (IaC) with Terraform.

## Technologies Used
- Amazon Web Services (AWS)
- Amazon S3
- Terraform
- HTML and CSS

## Project Objectives
- Create an S3 bucket using Terraform.
- Enable static website hosting.
- Upload an `index.html` file.
- Configure public access to the website.
- Access the website through the S3 website endpoint.

## Project Structure
```text
terraform-s3-static-website-proje2/
├── main.tf
├── provider.tf
├── variables.tf
├── outputs.tf
├── index.html
└── README.md
```

## Deployment Steps
1. Configure AWS credentials.
2. Initialize Terraform using `terraform init`.
3. Validate the configuration using `terraform validate`.
4. Apply the infrastructure using `terraform apply`.
5. Access the website using the generated S3 website endpoint.

## Live Website
[Visit My AWS S3 Static Website](http://yash-marsh-project2-static-site-590507089733.s3-website.ap-south-1.amazonaws.com)

## Author
Yash Pandey

**Project:** AWS S3 Static Website Hosting using Terraform
