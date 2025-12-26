# Terraform Remote Backend with S3 and DynamoDB

This Terraform project creates an S3 bucket and DynamoDB table for remote state management.

## Features
- Creates S3 bucket with versioning enabled
- Enables server-side encryption (SSE-S3)
- Creates DynamoDB table for state locking
- Configures public access blocking for security
- Outputs all necessary information for backend configuration

## Prerequisites
- AWS Account with IAM credentials
- Terraform v0.12 or higher
- AWS CLI configured

## Usage
```bash
# Initialize Terraform
terraform init

# Review plan
terraform plan

# Apply configuration
terraform apply

# Destroy resources
terraform destroy
