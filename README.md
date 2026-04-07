# AWS E-Commerce Platform Deployment

## Objective
To design and deploy a basic e-commerce application infrastructure using AWS cloud services.

## Services Used
- EC2 (Compute for hosting application)
- RDS (Managed database)
- S3 (Storage for static files)
- IAM (Access control and roles)
- VPC (Network configuration)
- Security Groups (Firewall rules)

## Architecture
The application is hosted on an EC2 instance within a VPC.  
The database is managed using RDS.  
Static content is stored in S3.  
Security is controlled using IAM roles and security groups.

## Steps Performed
1. Created a VPC and configured subnets
2. Launched an EC2 instance and installed web server
3. Configured security groups to allow HTTP/SSH access
4. Set up RDS database and connected it to EC2
5. Created S3 bucket for static storage
6. Configured IAM roles for secure access

## Key Configurations
- Opened port 80 (HTTP) and 22 (SSH) in security groups
- Connected EC2 to RDS using endpoint
- Assigned IAM role to EC2 for S3 access

## Output / Results
- Successfully hosted a web application on EC2
- Database connected and functioning
- Static files served from S3

## Key Learnings
- Basics of cloud architecture
- Importance of secure configurations
- Understanding of networking in AWS

## Note
All sensitive information such as access keys, IP addresses, and credentials have been removed for security purposes.
