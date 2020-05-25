#This is an analysis of Ansible versus Terraform, with a recommendation for using Ansible

#Author: Stephanie Weaver

#Date: 05/18/20


#Analysis

Ansible is an automation tool used for configuration management, software provisioning, and application deployment. 

Terraform, more of an infrastructure provisioning tool, allows the creation, management, and improvement of infrastructure; it is used for building, changing, and versioning infrastructure.

Although some of their functions overlap, Terraform is an orchestration tool and Ansible is a configuration management tool that can used together or independently.

While each tool would be useful in our organization and can be used simultaneously, Ansible offers an all-in-one configuration management technology. It does have a complex UI and relies on community support because 24X7 support is not offered. On the other hand, Terraform changes their APIs frequently, and only has limited documentation, which makes it more difficult to learn.

Applications that need application runtime environments to be very particular and stable, use Terraform. Ansible is more popular with organizations that benefit from its software provisioning and configuration management features.


#Proposal

I am proposing that we implement Ansible only at this time. There will be a learning curve, but it will take less time than learning Terraform. In addition, we can achieve more configuration management with Ansible. If we find that we need to better orchestrate infrastructure provisioning, we can take another look at using Terraform.
