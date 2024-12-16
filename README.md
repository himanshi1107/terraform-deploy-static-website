# 🌐 Deploy a Static Website on AWS Using Terraform

Welcome to the **Terraform Static Website Deployment** project! This repository demonstrates how to use **Terraform** to automate the deployment of a static website hosted on **AWS S3**. By leveraging Terraform, we ensure that the infrastructure is declarative, repeatable, and version-controlled.

## 🚀 Project Overview

This project automates the following tasks:

1. **Provision an S3 Bucket**: Create an S3 bucket for storing and serving the website files.
2. **Configure Static Website Hosting**: Enable static website hosting for the bucket.
3. **Upload Website Files**: Upload `index.html` and `style.css` to the bucket.
4. **Set Bucket Policies**: Set the necessary access policies to make the website publicly accessible.
5. **Output the Website URL**: Provide the URL where you can access the deployed website.

![image](https://github.com/user-attachments/assets/1bc37178-b539-4a7b-bdda-6c3dc3c3eebe)

## 🛠️ Prerequisites

Before you begin, ensure you have the following installed:

- [Terraform](https://www.terraform.io/downloads.html) - for managing the infrastructure.
- [AWS CLI](https://aws.amazon.com/cli/) - to configure AWS credentials.
- An **AWS Account** and an IAM User with sufficient permissions to manage S3 and related services.

## 🔥 How It Works

1. **Clone the Repository**: Start by cloning this repository to your local machine.
   
   ```bash
   git clone https://github.com/<your-username>/terraform-deploy-static-website.git
   cd terraform-deploy-static-website

2. **Configure AWS CLI**: Set up your AWS credentials using the AWS CLI.
   
   ```bash
   aws cofigure

3. **Initialize Terraform**: Initialize the Terraform working directory.
   
   ```bash
   terraform init
   
4. **Apply Terraform Configuration**: Apply the configuration to create the S3 bucket and upload the website files.

    ```bash
    terraform apply

🌍 Access the Website
  Once the infrastructure is deployed, you can access your static website using the URL provided by Terraform. The URL should look like this:

  ```php
    http://<bucket-name>.s3-website-<region>.amazonaws.com

