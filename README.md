# Terraform AWS

Repository for automating the provision of AWS services using Terraform

## To use this repository

1. Clone the repository
   `git clone https://github.com/anthonyallams/terraform-aws.git`
2. Create a virtual environment
   `python3 -m venv .venv`
3. Activate the virtual environment
   `source .venv/bin/activate`
4. Set your AWS Profile if you have more than one profile
   `export $AWS_PROFILE=<profile_name>`
5. Confirm your AWS Profile
   `echo $AWS_PROFILE`
6. Switch to the terraform folders and run the terraform commands
   `cd <folder_name>`
   `terraform init`
   `terraform plan`
   `terraform apply`
7. Deactivate the virtual environment
   `deactivate`
