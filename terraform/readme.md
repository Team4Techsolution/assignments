**Assignment: Build and Deploy Infrastructure in AWS**

**Objective**

Engineers are to build an infrastructure in AWS using Terraform and Ansible, following best practices in directory structure and state management. The assignment involves creating custom VPCs, deploying servers, setting up a load balancer, and deploying web content. Documentation and project management will be handled using Jira, Confluence, and GitHub.

**Requirements:**

1. **Terraform Setup:**

+ Use an S3 bucket as the backend for Terraform state file management.
+ Set up DynamoDB table locks for state locking.
+ Follow a good directory structure as taught in class, ensuring to have separate dev and prod environments.
+ Create custom modules that can be used in both environments.

2. **Infrastructure Resources:**

**Custom VPC:**

+ Create a custom VPC with public and private subnets.
+ Place one server in the private subnet and another server in the public subnet.
+ 
**Load Balancer:**
  
+ Deploy a load balancer that will route traffic to the instances in both the public and private subnets using Terraform.

3. **Server Configuration**

+ Use Ansible to install either Apache2 or Nginx on the servers.
+ Deploy a simple web content saying: Welcome to Class5 Team "your team name" Terraform and Ansible Assignment.
+ Ensure to follow a good directory structure for your Ansible setup. The structure should be organized and reusable, following best practices as taught in class 

4. **Project Management and Documentation:**

+ Create tickets on Jira to manage the project tasks.
+ Make documentation on Confluence or create a README file in the Git repository explaining your project.
+ Push the code to a GitHub repository, creating a new branch with your group name.


**Evaluation Criteria:**

+ Correctness and completeness of the Terraform and Ansible configurations.
+ Proper setup and use of S3 backend and DynamoDB locking.
+ Adherence to the directory structure and modularization.
+ Successful deployment of the web content.
+ Clarity and comprehensiveness of the documentation.
+ Proper usage of Jira for task management.
+ This assignment aims to help you gain hands-on experience with Terraform, Ansible, and AWS infrastructure management, along with project documentation and task management practices
+ Ansible configuration
  
