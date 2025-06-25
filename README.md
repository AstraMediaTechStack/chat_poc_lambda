# Chat POC

- Python
- AWS Lambda Function
- Terraform

```sh
terraform init --upgrade # as needed
terraform plan
```

And then
```sh
# Using default values, given terraform.tfvars
terraform apply

# Or
terraform apply \
  -var="agent_id=..." -var="agent_alias_id=..." -var="s3_bucket=..."
```
