## : Getting Started with Terraform

#### Introduction to Terraform and IaC

#### Installing Terraform on MacOS, Linux and Windows

#### Setting up Terraform for AWS

#### Writing Your First Terraform Code

Start writing actual Terraform code with a simple example. The basic structure of a Terraform configuration file and how to define resources using the HCL language.

### Terraform Lifecycle

Understand the lifecycle of terraform. Terraform `init`, `plan` and `apply`.

#### Launching an EC2 Instance

Take your skills up a notch by provisioning an EC2 instance on AWS using Terraform. Explore attributes like instance type, AMI, and tags to customize your instance.

#### Terraform State Basics

## Advanced Terraform Configuration

#### Understanding Providers and Resources

Deepen your knowledge of providers and resources. Explore the role of different providers for various cloud platforms and understand how resources define infrastructure components.

#### Variables and Outputs in Terraform

Discover the power of variables for dynamic configurations. Learn how to define, declare, and utilize variables effectively. Explore outputs to retrieve and display essential information.

#### Conditional Expressions and Functions

Elevate your configurations with conditional expressions, adding logic to your code. We'll introduce you to Terraform's built-in functions for tasks like string manipulation and calculations.

#### Debugging and Formatting Terraform Files

Master the art of debugging Terraform configurations.Plus, learn why proper formatting with terraform fmt is crucial.

##  Building Reusable Infrastructure with Modules

#### Creating Modular Infrastructure with Terraform Modules

Unlock the potential of reusability with Terraform modules. Understand how modules enable you to create shareable and organized infrastructure components.

#### Local Values and Data Sources

Simplify complex expressions using local values. Dive into data sources and learn how to fetch data from existing resources or external systems, enhancing your configurations' flexibility.

#### Using Variables and Inputs with Modules

Explore the versatility of using variables within modules to customize their behavior. Learn how inputs work within modules and the benefits they offer.

#### Leveraging Outputs from Modules

Utilize module outputs to access critical information or propagate data to your root configuration. Learn how to make your modules more informative and useful.

#### Exploring Terraform Registry for Modules

Embark on a journey through the Terraform Registry. Discover pre-built, community-contributed modules and learn how to incorporate them into your own configurations.

## Collaboration and State Management

#### Collaborating with Git and Version Control

Collaborate effectively using Git and version control. Grasp fundamental Git commands such as cloning, pulling, and pushing repositories to enhance teamwork.

#### Handling Sensitive Data and .gitignore

Tackle security challenges associated with sensitive data in version control. Explore the importance of .gitignore to exclude sensitive files from being committed.

#### Introduction to Terraform Backends

Uncover the role of Terraform backends in remote state storage. Learn why they're essential for maintaining infrastructure state and configurations.

#### Implementing S3 Backend for State Storage

Get hands-on experience configuring an S3 bucket as a backend for remote state storage. Understand how this setup improves collaboration and state management.

#### State Locking with DynamoDB

Dive into state locking and the prevention of concurrent updates. Implement state locking using DynamoDB as a backend mechanism, ensuring state consistency.

