# Chat

- Python
- AWS Lambda Function


- For prod lambda, dynamodb, etc
```sh
terraform init --upgrade # as needed
terraform plan
```

And then
```sh
# Using default terraform.tfvars
terraform apply

# Or
terraform apply \
  -var="agent_id=..." -var="agent_alias_id=..." -var="s3_bucket=..."
```
