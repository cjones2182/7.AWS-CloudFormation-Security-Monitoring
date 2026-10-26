AWS CloudFormation Security Project

This project demonstrates how to deploy and secure AWS infrastructure using CloudFormation. The infrastructure includes a VPC with public and private subnets, EC2 instances, an Application Load Balancer, Internet Gateway, and NAT Gateway.

Network segmentation isolates private resources from direct internet access, while security groups restrict traffic between resources. A bastion host provides controlled SSH access to private EC2 instances.

AWS WAF protects against common web vulnerabilities, SQL injection, and malicious requests. AWS CloudTrail records API activity and stores logs in Amazon S3 for security auditing and investigations.

The project focuses on defense-in-depth, least-privilege access, network security, centralized logging, and Infrastructure as Code (IaC).