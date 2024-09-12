export TF_VAR_secret_id="xxxxxx"
export TF_VAR_secret_key="xxxxxx"

terraform init
terraform plan
terraform apply --auto-approve

terraform destroy -auto-approve