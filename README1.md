# Terraform Hands-On


## Install Terraform 
   Refer this site to install terraform on ubuntu - https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli

## Follow these steps

1. Clone this repository
   ```
   https://github.com/aditya281121/write_your_first_terraform_project.git
   cd /aws/local_state
   ls
2. Run the main.tf file
   ```
   terraform init
3. Dry run the terraform file
   ```
   terraform plan
5. Install AWS CLI in the linux vm
   Refer this site - https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
6. Connect the AWS cli with the aws console using access keys
   ```
   aws configure
7. Finally provision the infrastructure
   ```
   terraform apply
   ls -ltr
8. terraform.tf state file is very important understand it clearly
   ```
   vim terraform.tfstate  


