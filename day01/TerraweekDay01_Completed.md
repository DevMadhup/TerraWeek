# TerraWeek Day 1

## Day 1: Introduction to Terraform and Terraform Basics

### What is Terraform and how can it help you manage infrastructure as code?
### Ans:- 
         Terraform is IAAC ( Infrastructure As A Code ) tool which used to build and change infrastructure.
         
         It helps us to manage infrastructure as code in following ways:
         1) Scope - Identify the infrastructure for your project.
         2) Author - Write the configuration for your infrastructure.
         3) Initialize - Install the plugins Terraform needs to manage the infrastructure.
         4) Plan - Preview the changes Terraform will make to match your configuration.
         5) Apply - Make the planned changes.
  

### Why do we need Terraform and how does it simplify infrastructure provisioning?
### Ans:-
         Terraform helps to autmomate the infrastructure with the help of terraform configuration files. It reduces 
         i) cost
         ii) human errors etc.
         
         It makes infrastructure provisioning Simple and Fast. 
         With a simple configuartion file we can manage multiple projects.
         Terraform increses speed of creating infrastructure, automation. 
         
         
### How can you install Terraform and set up the environment for AWS, Azure, or GCP?
### Ans:-
         Installation:
         
         wget -O- https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg
         echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee                    /etc/apt/sources.list.d/hashicorp.list
         sudo apt update && sudo apt install terraform
         
         
         
### Explain the important terminologies of Terraform with the example at least (5 crucial terminologies).
### Ans:- 
         1) Provider
         - A provider is a plugin that lets Terraform manage an external API.
         2) Resource
         3) Module
         4) Variable 
         5) Output
         
Attach code snippets and steps wherever necessary and post your learnings on LinkedIn

Feel Free to reach out to any of the TWS Community Builders / Leaders

Watch this [Reference Video](https://www.youtube.com/live/965CaSveIEI?feature=share)

Happy Learning 
