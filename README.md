# OpenCV-Face-Identification-
This is a face identification program in python which makes use of OpenCV library of python. It first detects the face of the user then takes records with the help of 100 images and saves it in a folder called 'faces'(need to be made manually if doesnt exist). 
Then the model is trained so the the user is identified when he/she appears the next time.
After the identification of the user a terraform file is executed which consist of code to launch a VPC(Virtual Private Cloud) in AWS.

pre-requisite: Terraform software and AWSCLI to be installed.

Technologies integrated:

## Python 
## OpenCV
## CNN
## Terraform
## AWS

What is Terraform?

Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently. Terraform can manage existing and popular service providers as well as custom in-house solutions.
Configuration files describe to Terraform the components needed to run a single application or your entire datacenter. Terraform generates an execution plan describing what it will do to reach the desired state, and then executes it to build the described infrastructure. As the configuration changes, Terraform is able to determine what changed and create incremental execution plans which can be applied.
The infrastructure Terraform can manage includes low-level components such as compute instances, storage, and networking, as well as high-level components such as DNS entries, SaaS features, etc.

The key features of Terraform are:

» Infrastructure as Code: 
Infrastructure is described using a high-level configuration syntax. This allows a blueprint of your datacenter to be versioned and treated as you would any other code. Additionally, infrastructure can be shared and re-used.

» Execution Plans: 
Terraform has a "planning" step where it generates an execution plan. The execution plan shows what Terraform will do when you call apply. This lets you avoid any surprises when Terraform manipulates infrastructure.

» Resource Graph: 
Terraform builds a graph of all your resources, and parallelizes the creation and modification of any non-dependent resources. Because of this, Terraform builds infrastructure as efficiently as possible, and operators get insight into dependencies in their infrastructure.

» Change Automation: 
Complex changesets can be applied to your infrastructure with minimal human interaction. With the previously mentioned execution plan and resource graph, you know exactly what Terraform will change and in what order, avoiding many possible human errors.

Amazon Virtual Private Cloud:

Amazon Virtual Private Cloud (Amazon VPC) is a service that lets you launch AWS resources in a logically isolated virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways. You can use both IPv4 and IPv6 for most resources in your virtual private cloud, helping to ensure secure and easy access to resources and applications.

As one of AWS's foundational services, Amazon VPC makes it easy to customize your VPC's network configuration. You can create a public-facing subnet for your web servers that have access to the internet. It also lets you place your backend systems, such as databases or application servers, in a private-facing subnet with no internet access. Amazon VPC lets you to use multiple layers of security, including security groups and network access control lists, to help control access to Amazon EC2 instances in each subnet.

Benefits of Using Amazon Virtual Private Cloud (Amazon VPC)

- Secure and monitored network connections:

Amazon VPC provides advanced security features that allow you to perform inbound and outbound filtering at the instance and subnet level. Additionally, you can store data in Amazon S3 and restrict access so that it’s only accessible from instances inside your VPC. Amazon VPC also has monitoring features that let you perform functions like out-of-band monitoring and inline traffic inspection, which help you screen and secure traffic.

- Simple set-up and use:

With Amazon VPC's simple set-up, you spend less time setting up, managing, and validating, so you can concentrate on building the applications that run in your VPCs. You can create a VPC easily using the AWS Management Console or Command Line Interface (CLI). Once you select from common network setups and find the best match for your needs, VPC automatically creates the subnets, IP ranges, route tables, and security groups you need. After configuring your network, you can easily validate it with Reachability Analyzer.

- Customizable virtual network:

Amazon VPC helps you control your virtual networking environment by letting you choose your own IP Address range, create your own subnets, and configure route tables to any available gateways. You can customize the network configuration by creating a public-facing subnet for your web servers that has access to the internet. Place your backend systems, such as databases or application servers, in a private-facing subnet. With Amazon VPC, you can ensure that your virtual private cloud is configured to fit your specific business needs.
