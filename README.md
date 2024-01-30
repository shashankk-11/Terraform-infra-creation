# Terraform-infra-creation
Learning cloud infrastructure creation with terrafrom 


## useful documentation links 

- [Terraform Language Documentation](https://www.terraform.io/docs/language/index.html)
- [Resource: aws_security_group](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/security_group)
- [Resource: aws_instance](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance)    

## Steps to setup terraform
### Step 1: Initialize Terraform
```
terraform init
```

### Step 2: Plan Resources
```
terraform plan -var-file="vars/dev-west-2.tfvars"
```

### Step 3: Apply Resources
```
terraform apply -var-file="vars/dev-west-2.tfvars"
```

### Added set of plugins for jenkins 

Docker Pipeline<br>
kubernates cli<br>
aws credentials<br>
amazon ecr

