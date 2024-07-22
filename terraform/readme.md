Assignment: Build and Deploy Infrastructure in AWS
Objective:
Students are to build an infrastructure in AWS using Terraform and Ansible, following best practices in directory structure and state management. The assignment involves creating custom VPCs, deploying servers, setting up a load balancer, and deploying web content. Documentation and project management will be handled using Jira, Confluence, and GitHub.

Requirements:
Terraform Setup:

Use an S3 bucket as the backend for Terraform state file management.
Set up DynamoDB table locks for state locking.
Follow a good directory structure as taught in class, ensuring to have separate dev and prod environments.
Create custom modules that can be used in both environments.
Infrastructure Resources:

Custom VPC:
Create a custom VPC with public and private subnets.
Place one server in the private subnet and another server in the public subnet.
Load Balancer:
Deploy a load balancer that will route traffic to the instances in both the public and private subnets using Terraform.
Server Configuration:

Use Ansible to install either Apache2 or Nginx on the servers.
Deploy a simple web content saying: Welcome to Class5 Team "your team name" Terraform and Ansible Assignment.
Project Management and Documentation:

Create tickets on Jira to manage the project tasks.
Make documentation on Confluence or create a README file in the Git repository explaining your project.
Push the code to a GitHub repository, creating a new branch with your group name.
Instructions:
Terraform Directory Structure:

css
Copy code
├── terraform
│   ├── modules
│   │   └── <custom_modules>
│   ├── environments
│   │   ├── dev
│   │   └── prod
├── backend.tf
├── provider.tf
├── variables.tf
├── main.tf
└── outputs.tf
Setting up Backend and State Locking:

Configure backend.tf to use the S3 bucket for the state file.
Configure DynamoDB table for state locking.
Creating Custom VPC and Instances:

Use Terraform scripts to create a custom VPC with public and private subnets.
Deploy one server in the private subnet and another server in the public subnet.
Set up a load balancer to route traffic to both instances.
Using Ansible for Configuration:

Write Ansible playbooks to install Apache2 or Nginx.
Deploy the web content as specified.
Documentation and Version Control:

Create Jira tickets for different tasks involved in the project.
Document the project in Confluence or a README file in the GitHub repository.
Push all code to GitHub in a new branch named after your group.
Submission:
Ensure all components (Terraform scripts, Ansible playbooks, and documentation) are complete.
Submit the GitHub repository link with the specific branch name.
Ensure all Jira tickets are updated and reflect the work done.
Provide access to the Confluence documentation if used.
Evaluation Criteria:
Correctness and completeness of the Terraform and Ansible configurations.
Proper setup and use of S3 backend and DynamoDB locking.
Adherence to the directory structure and modularization.
Successful deployment of the web content.
Clarity and comprehensiveness of the documentation.
Proper usage of Jira for task management.
This assignment aims to help you gain hands-on experience with Terraform, Ansible, and AWS infrastructure management, along with project documentation and task management practices
