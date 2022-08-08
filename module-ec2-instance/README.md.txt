terraform init
terraform plan --var-file .\values.tfvars
terraform apply --var-file .\values.tfvars
terraform destroy --var-file .\values.tfvars