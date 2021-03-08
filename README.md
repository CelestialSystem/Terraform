# Terraform
Provision Azure/AWS machines

Once creating the script is done, please run the below commands to format, validate and initialize the terraform code.

terraform fmt

terraform validate

terraform init

To view or to create the execution plan, please run:

terraform plan

If you are satisfied with the execution plan, please apply the code to create the VMs:

terraform apply --auto-approve

Note: To understand the terraform blocks and its usage, please follow the terraform official guide, as it is out of scope for this article.


When you don't need these resources, please run:

terraform destroy
