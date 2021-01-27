# Terraform-modules-VPC,subnets,eip's,natgateways,igw,ec2-instances
Terraform modules for vpc, subnets, ecr-repo, ecs
# commands:-
# 1.Initialize the terraform run
```sh
terraform init
```

# 2.Plan the script to make sure what exactly it's creating and redirect the output to JSON
```sh
terraform plan --out=outputs.json --var-file=./env/QA.tfvars
```
# 3.Apply the terraform 
```sh
terraform apply "outputs.json"
```
