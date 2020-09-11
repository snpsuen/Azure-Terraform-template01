# terraform-azure-template01
Sample terraform IaC for deploying Azure resources based on https://github.com/PacktPublishing/Learning_DevOps/tree/master/CHAP02/terraform_vars_interp

To use or test out the code, git clone https://github.com/snpsuen/terraform-azure-template01 and cd the repo directory <br>
(1)  Export the Azure environment variables: <br>
export ARM_SUBSCRIPTION_ID=xxxxx-xxxxx-xxxx-xxxx <br>
export ARM_CLIENT_ID=xxxxx-xxxxx-xxxx-xxxx <br>
export ARM_CLIENT_SECRET=xxxxxxxxxxxxxxxxxx <br>
export ARM_TENANT_ID=xxxxx-xxxxx-xxxx-xxxx <br>
<br>
(2)  Edit terraform.tfvars as necessary. <br>
<br>
(3) Invoke the terraform commands in order: <br>
3.1  terraform init <br>
3.2  terraform plan <br>
3.3  terraform apply <br>
