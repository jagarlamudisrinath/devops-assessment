# Terraform 
Launch AWS EC2 instance using terraform.

 

$cd Lvl1/terraform

update the main.tf file with AWS access_key and secret_key

initialize working directory with terraform init 

$terraform init

terraform plan command is used to create an execution plan

$terraform plan

create the EC2 instance by using following command.

$terraform apply

It will generate pem file nginx.pem which will used for EC2 authentication.
The public ip address of EC2 will print in the terraform output. 
we need to update ip address in inventory file of Ansible(Lvl1/ansible/inventory).

# Ansible 


