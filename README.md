# aws-webapp-lift-shift
Web Application setup using AWS Instances using Lift and Shift 

Project 02 DevOps

Creating a Multi Tier Web Application on AWS EC2 Instances for production.

The webapp created in Project 01 is deployed in aws using lift and shift method.

VMs are replaced by EC2 Instances.
Nginx is replaced by ELB (Elastic Load Balancer).
Autoscaling is included to handle workload as required.
S3/EFS is used for storage.
Route 53 for the DNS service (For Backend services).
Git Bash is used for CLI.
Visual Studio Code as an IDE.

The instances are launched manually. The artifact is built in local machine and uploaded to S3.
