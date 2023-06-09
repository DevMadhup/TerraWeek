# TerraWeek Day 2

## Task 1: Familiarize yourself with HCL syntax used in Terraform
### Learn about HCL blocks, parameters, and arguments
### Ans:-
         1) Blocks 
          - We can write actual configuration code in between blocks only. 
            We can create block by using {}.
            
          Syntax:
                 <block_name> <resource_type> <resource_name> {
                 
                 }
          Example:
                 resource "local_file" "file1"{
                      filename = "/home/ubuntu/file1.txt"
                      content = "I am a devops engineer"
                 }
          
         2) Arguments:
          - Anything written inside the block is called as arguments.
          
          Syntax:
                 <block_name> <resource_type> <resource_name> {
                              <argument1> = ""
                              <argument2> = ""
                 }
          Example:
                 resource "local_file" "file1"{
                      filename = "/home/ubuntu/file1.txt"
                      content = "I am a devops engineer"
                 }
                 
- Explore the different types of resources and data sources available in Terraform

## Task 2: Understand variables, data types, and expressions in HCL
- Create a variables.tf file and define a variable
- Use the variable in a main.tf file to create a "local_file" resource

## Task 3: Practice writing Terraform configurations using HCL syntax
- Add required_providers to your configuration, such as Docker or AWS
- Test your configuration using the Terraform CLI and make any necessary adjustments

Attach code snippets and steps wherever necessary and post your learnings on LinkedIn
Feel Free to reach out to any of the TWS Community Builders / Leaders
Watch this 👉 https://youtu.be/kqJIKjkJ1Lo

# Happy Learning🎉🚀
