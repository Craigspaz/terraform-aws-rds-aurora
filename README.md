# terraform-aws-aurora-postgresql
To deploy this module, do the following:
1. Sign up for [Terraform Cloud](https://app.terraform.io/signup/account). (There is a free tier available.)
2. Clone this **aws-quickstart/terraform-aws-aurora_postresql** directory.

        git clone https://github.com/aws-quickstart/terraform-aws-aurora_postresql.git

3. In the root directory, run `terraform login` to ensure you are authenticated into Terraform Cloud.
4. Run `export TERRAFORM_CONFIG="$HOME/.terraform.d/credentials.tfrc.json"`.
5. Run `terraform init` to initialize the workspace.
6. Run `terraform apply`.
7. Change directory by running `cd ./setup_env`.
8. Run `terraform init` to initialize the workspace.
9. Run `terraform apply` and follow the prompts.
