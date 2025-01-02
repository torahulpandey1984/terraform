# terraform

1. 'terrafrom provider'
2. `terraform init`
3. `terraform plan`
4. `terraform apply --auto-approve`
5. `terraform destroy`
6. 'terraform state list'
7. 'terraform state  show aws_subnet.dev-subnet-1'
8. terrafrom validate
9. terrafrom fmt 

output 
`
output "vpc-id" {
value = aws_vpc.development-vpc.id
}
`

variables 
define variables in different file dev,test 
`dev.tfvars,test.tfvars`
`terraform apply -var-file dev.tfvars`
default variable file `terraform.tfvars`
command prompt and parameter is another way not great . 
`
variable "subnet_cidr_block" {
description = "cidr block subnet " 
}
`
to use `var.subnet_cidr_block`




