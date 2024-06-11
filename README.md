# Terraform
Terraform is an infrastructure as a code tool that lets you define cloud and on-prem resources in human-readable configuration files that you can version, reuse, and share. You can then use a consistent workflow to provision and manage your infrastructure throughout its lifecycle. Terraform can manage low-level components like computing, storage, and networking resources, as well as high-level components like DNS entries and SaaS features.
## Terraform Tutorial
~~~
sudo yum install wget unzip
wget https://releases.hashicorp.com/terraform/0.12.16/terraform_0.12.16_linux_amd64.zip
sudo unzip ./terraform_0.12.16_linux_amd64.zip -d /usr/local/bin/
terraform --version

mkdir terraform
cd terraform

nano main.tf

~~~
Add content to the main.tf 

### 4 Steps
~~~
terraform init
terraform plan
terraform apply
terraform destroy
~~~
## Terraform Demo
