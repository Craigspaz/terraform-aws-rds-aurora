# terraform-aws-rds-aurora (Developer Preview)
Authors: David Wright (dwright@hashicorp.com) and Tony Vattahil (tonynv@amazon.com)

To deploy this module, do the following:
1. Sign up for [Terraform Cloud](https://app.terraform.io/signup/account). (There is a free tier available.)
2. Clone this **aws-quickstart/terraform-aws-aurora_postresql** directory.

        git clone https://github.com/aws-quickstart/terraform-aws-aurora_postresql.git

3. Change directory to the root directory.

        cd terraform-aws-aurora_postresql

4. Run `terraform login` to ensure you are authenticated into Terraform Cloud.
5. Run `export TERRAFORM_CONFIG="$HOME/.terraform.d/credentials.tfrc.json"`.
6. Change directory by running `cd ./setup_env`.
7. Run `terraform init`.
8. Run `terraform apply`.
9. To deploy a VPC, change directory by running `cd ../deploy_new_vpc`.
10. Run `terraform init`.
11. Run `terraform apply`.
