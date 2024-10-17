Name: GUNTUPALLI HRUSHIKESH

Company: CODTECH IT SOLUTIONS

ID: CT08DS8148

Domain: DEVOPS

Duration: SEPTEMBER TO OCTOBER

Mentor:

Project: INFRASTRUCTURE AS CODE WITH TERRAFORM

Overview of Infrastructure as Code (IaC) with Terraform on AWS

Objective:

*Utilize Terraform to automate the provisioning, management, and destruction of cloud infrastructure resources on AWS. This project enables you to learn how to define and manage your infrastructure as code, making deployments more reliable and repeatable

Key Concepts:

*Infrastructure as Code (IaC):
IaC is the practice of managing and provisioning computing infrastructure through machine-readable definition files, rather than physical hardware configuration or interactive configuration tools.

Terraform:

*An open-source tool for building, changing, and versioning infrastructure safely and efficiently. It uses configuration files to define the desired state of infrastructure and manages the lifecycle of that infrastructure.

AWS Resources:

*In this project, you'll focus on provisioning resources such as EC2 instances, VPCs, subnets, security groups, and more.

Implementation Steps:

Setup Terraform:

*Install Terraform on your local machine or a CI/CD environment. Ensure you have access to your AWS account with appropriate permissions.

Write Terraform Configuration Files:

*Create .tf files to define your infrastructure. For example, a basic configuration for an AWS EC2 instance might include:
*Provider: Specify the AWS provider and region.
*Resources: Define resources like EC2 instances, security groups, and VPCs.
*Variables: Use variables for configurable parameters (e.g., instance type, AMI ID).
*Outputs: Define outputs to display useful information after the infrastructure is provisioned.

Initialize Terraform:

*Run terraform init to initialize the directory containing your configuration files. This command downloads necessary provider plugins

Plan Infrastructure Changes:

*Use terraform plan to create an execution plan. This command shows you what changes Terraform will make to your infrastructure.

Apply Configuration:

*Execute terraform apply to provision the resources defined in your configuration files. Review the changes and confirm to proceed.

Manage Infrastructure:

*Make updates to your configuration files as needed and repeat the plan and apply steps to modify your infrastructure.
*Use terraform show to view the current state of your infrastructure.

Destroy Infrastructure:

*When you no longer need the resources, run terraform destroy to remove all resources defined in your configuration. This command is crucial for avoiding unnecessary costs.
