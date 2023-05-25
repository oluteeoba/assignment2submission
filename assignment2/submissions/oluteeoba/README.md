## My name is oluteeoba and please file below my submission for assignment2

## Kubernetes, Docker, Containerisation and Virtualisation

1. Virtual Machine Advantages

* Decades of virtualization expertise enables access to a robust set of VM management and security tools
* VMs offer the ability to run multiple applications requiring different OSs on a single piece of infrastructure
* VMs emulate an entire computing environment, including all OS resources
* VMs simplify the portability and migration between on-premises and cloud-based platforms
* There is a vast, established VM ecosystem and marketplace with industry leaders such as VMware
 

Virtual Machine Disadvantages

* VM images typically consume gigabytes and thus take longer to backup or migrate between platforms
* Because they encapsulate the entire server including OS, a physical server can support fewer VMs than containers
* VM Spin-up time can take minutes

Container Advantages

* Containers are more lightweight than VMs, as their images are measured in megabytes rather than gigabytes
* Containers require fewer IT resources to deploy, run, and manage
* Containers spin up in milliseconds
* Since their order of magnitude is smaller
* A single system can host many more containers as compared to VMs
 

Container Disadvantages

* All containers must run atop the same OS – no mix and match of OSs or versions
* Containers may be less secure than VMs since the underlying OS is shared
* Containers are a newer technology, and the ecosystem is still evolving


2.

A DOCKER IMAGE is a file used to execute code in a Docker container. Docker images act as a set of instructions to build a Docker container, like a template. Docker images also act as the starting point when using Docker. An image is comparable to a snapshot in virtual machine (VM) environments

How to Create a Docker Image
*Write a Dockerfile for your application.
*Build the image with docker build command.
*Host your Docker image on a registry.
*Pull and run the image on the target machine.


A CONTAINER is an isolated environment for your code. This means that a container has no knowledge of your operating system, or your files. 

RUNNING A CONTAINER
It runs on the environment provided to you by Docker Desktop. This is why a container usually has everything that your code needs in order to run, down to a base operating system.

## Linux administration and shell scripting

1. XXXX

## CICD, Infrastructure as as Code (IaC), Terraform, Packer and Ansible

WHAT IS INDEMPOTENCE?
Idempotence is any function that can be executed several times without changing the final result beyond its first iteration. Idempotence is a technical word, used in mathematics and computer science, that classifies a function's behavior.

BENEFITS OF ADOPTING DEVOPs IN AN ORGANISATION
*Faster, better product delivery.
*Faster issue resolution and reduced complexity.
*Greater scalability and availability.
*More stable operating environments.
*Better resource utilization.
*Greater automation.
*Greater visibility into system outcomes.
*Greater innovation.


BENEFITS OF PROVOSIONING INFRACSTRUCTURE USING TERRAFORM AND ANSIBLE
TERRAFORM excels as a cloud infrastructure provisioning and deprovisioning tool with an IaC approach. It's a specific tool with a specific purpose. 

ANSIBLE offers an all-purpose, cross-domain automation solution. Both have active open source communities and well-supported downstream commercial products.
Very simple to set up and use: No special coding skills are necessary to use Ansible's playbooks (more on playbooks later).
Powerful: Ansible lets you model even highly complex IT workflows. 
Flexible: You can orchestrate the entire application environment no matter where it's deployed.

5 PROVISIONING AND CONFIGURATION MANAGEMENT TOOLS 

1.ANSIBLE

ADVANTAGES
*Very simple to set up and use:
*No special coding skills are necessary to use Ansible's playbooks . 
*Powerful: Ansible lets you model even highly complex IT workflows.
*Flexible: You can orchestrate the entire application environment no matter where it's deployed.

DISADVANTAGES
*Insufficient User Interface · 
*Lack of any Notion of State · 
*Limited Windows Support · 
*Ansible does not have Experience.

2. PUPPET

ADVANTAGES
Puppet's leveraging of Infrastructure as Code (IAC) features allow for efficient and flexible resolution of issues with version control, continuous delivery, peer review, and automated testing and deployment.

DISADVANTAGES
Difficult to Instal and Setup: Puppet was designed to process more complex functions and tasks for system administrators. Unlike Ansible, they are difficult to set up by common users. Difficult to Use: Not every programmer can run a puppet to fix complex tasks.

3. CF ENGINE
ADVANTAGES
To automate the packaging and provisioning of software into an organization's operational IT environment

DISADVANTAGE
A typical problem is separation and cross referencing. It is highly recommended to separate every single function into one file and use imports. This way an administrator does not have to repeat every configured feature for multiple hosts or types of host

4.SALT
ADVANTAGES
Authentication − Salt manages simple SSH key pairs for authentication. Secure − Salt manages secure data using an encrypted protocol. Fast − Salt is very fast, lightweight communication bus to provide the foundation for a remote execution engine.

5. CHEF
ADVANTAGES
Chef is a Configuration management DevOps tool that manages the infrastructure by writing code rather than using a manual process so that it can be automated, tested and deployed very easily. Chef has Client-server architecture and it supports multiple platforms like Windows, Ubuntu, Centos, and Solaris etc

DISADVANTAGES
It needs constant babying so that people who are working should not mess up with others cookbooks. Only Chef solo is available. In the current situation, it is only a good fit for AWS cloud. It is not very easy to learn if the person is not familiar with Ruby.


COMPARISM BETWEEN MUTABLE SERVER AND IMMUTABLE SERVER
Traditional mutable infrastructures originally developed when the use of physical servers dictated what was possible in their management and continued to develop as technology improved over time. The benefits of an immutable infrastructure include more consistency and reliability in your infrastructure and a simpler, more predictable deployment process. It mitigates or entirely prevents issues common in mutable infrastructures, like configuration drift and snowflake servers.

In contrast, immutable infrastructures were designed from the start to rely on virtualization-based technologies for fast provisioning of architecture components, like cloud computing's virtual servers. The speed and low cost of creating new virtual servers make the immutable server infrastructure, or immutable infrastructure paradigm, practical.

The benefits of an immutable infrastructure include more consistency and reliability in your infrastructure and a simpler, more predictable deployment process. It mitigates or entirely prevents issues common in mutable infrastructures, like configuration drift and snowflake servers.

What is an immutable server infrastructure?
The concept of immutable server infrastructure is to build the server infrastructure components to exact specifications. No deviation, no changes. It is what it is. When a change to a specification is required, a whole new set of server infrastructure is provisioned based on the updated requirements, and the previous server infrastructure is taken out of service as it is obsolete.

Virtualization (both software and hardware) across networking, servers and storage is the primary technology that makes immutable infrastructure possible at any scale. Virtualization is at the core of the modern data center and makes cloud computing possible. Provisioning and retiring physical hardware to accommodate every change is cost and time prohibitive. That is why mutable infrastructure has been the norm in all but the biggest companies until very recently, when virtualization became commonplace. Containers (ex: Docker) are the newest trend in the immutable infrastructure space and are simply another virtualization layer.

3 best way to make an object reproducible: There are three basic steps:

Document how to create the object.
Create scripts that will build and assemble the components into the object as described in the documentation.
Automate the process.
Track each version of the documentation and script through version control to record changes.

Infrastructure-as-code is the ideal way to create immutable infrastructure. Run it on virtualized platforms and public cloud computing providers, which is known as DevOps.

 SOME COMMERCIAL AND ENTERPRISE TOOLS AND THEIR RECOMMENDATIONS

1. Lightspeed for inventory management tool
Lightspeed is a great one to start off our list when it comes to inventory management. For many businesses, taking account of stock, whether it’s all sold online, in-store or both is challenging. The bigger a business becomes, the more inventory there is to be managed. This can be made easier with an inventory management tool.

2. Trello for team collaboration and communication
For team collaboration and communication, Trello is a great one to help bring together team members within a department to those across the organization as a whole. It can also be useful when you’re working with external groups or individuals and required a centralized hub for communication task management.

3. Hubspot for marketing
Hubspot is widely known as being an effective management platform for all things marketing. You’ll have everything you need to help run campaigns successfully and that deliver great results. 
Ultimately, you want to generate leads and improve conversions of those leads. With Hubspot, the platform helps sync up your teams and engaging your audience through campaigns that are aligned with your business’ potential.

4. nTask for smaller businesses and entrepreneurs 
For those smaller businesses and solopreneurs with few projects at a time, the business can be managed with nTask.
This business software helps to manage all elements of the business and any employees that you have. It is a little complex to understand, so it will take some training in order to get used to.

IMPERATIVE AND DECLARATIVE WAY OF PROVISIONING INFRACSTRUCTURE

IaC. The core of a declarative style language/tool is that you say what, whereas in an imperative style language you say how. In the case of IaC; for declarative you specify a list of resources you would like, whereas for imperative you specify a list of commands to run to create the resources that you want.


GITHUB ACTION ROLES CICD AUTOMATED INTEGRATION TOOLCHAIN
CI using GitHub Actions offers workflows that can build the code in your repository and run your tests. Workflows can run on GitHub-hosted virtual machines, or on machines that you host yourself.

WHAT IS A RUNNERIN PROVISIONING PIPELINE
Runners allows you to run builds in Pipelines on your own infrastructure, and you won't be charged for the build minutes used by your self-hosted runners. The following guides help you configure your operating system with Pipelines to use runners within your repositories.

GITHUB ACTION CODE TO TRIGGER GITHUB ACTION WORKFLOW
GitHub Actions uses YAML syntax to define the workflow. Each workflow is stored as a separate YAML file in your code repository, in a directory named .github/ ...

GITHUB ACTIONS
GitHub Actions includes a collection of variables called contexts and a similar collection of variables called default variables. These variables are intended for use at different points in the workflow: Default environment variables: These environment variables exist only on the runner that is executing your job.


## System Architecture and Application Design, Cloud Computing (AWS)

1. XXXX


## Site Reliability Engineering (SRE), Troubleshooting, Observability

1Always ask questions to know what the file is all about thas is the reason for the script
We ensuring safety by System metrics monitoring
LOg in
Tracing
Distribution



## DevOps and Agile Transformation principles and methodology

1. Learn security best practices

2. Cloud computing and visualisation

3. Learn container orchestration,system login,monitoring and observability

4. Linux

5. Learn infracstructure automation


## New commands logs - Enter up to ten new commands you have learnt this week

| Number      | Commands | What does it do and how might you check its effect     |
| :---        |    :----:   | :---  |
| 1  | rm -rf      | to delete folder or file|
| 2  | cd            | to change into directory  |
| 3  | ls -la       | to chech what is inside a hidden folder   |
| 4  | cd ../       | to go a step upward   |
| 5  | mkdir           | to make directory  |
| 6  | git init       | to track a file  |
| 7  | code .       | to power up VS code   |
| 8  | git add .       | adds a change in the working directory to the staging area   |
| 9  | git push       | to push from my local machine into a local repo   |
| 10 | git remote -v       | to check where the address of a repo is pointing to   |

## Glossary of the week - Enter new technical words you have learnt this week and their meanings.

| Number   | Word | Meaning     |
| :---     | :----:   |  :---  |
| 1  | XXXXXXXX       | YYYYYYYY   |
| 2  | XXXXXXXX       | YYYYYYYY   |
| 3  | XXXXXXXX       | YYYYYYYY   |
| 4  | XXXXXXXX       | YYYYYYYY   |
| 5  | XXXXXXXX       | YYYYYYYY   |
| 6  | XXXXXXXX       | YYYYYYYY   |
| 7  | XXXXXXXX       | YYYYYYYY   |
| 8  | XXXXXXXX       | YYYYYYYY   |
| 9  | XXXXXXXX       | YYYYYYYY   |
| 10 | XXXXXXXX       | YYYYYYYY   |

