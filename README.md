# terraform

1. 'terrafrom provider'
2. `terraform init`
3. `terraform plan`
4. `terraform apply --auto-approve`
5. `terraform destroy`
6. 'terraform state list'
7. 'terraform state  show aws_subnet.dev-subnet-1'

output 
`
output "vpc-id" {
value = aws_vpc.development-vpc.id
}
`


