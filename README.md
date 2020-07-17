# terraform-course
Thanks https:/github.com/wardviaene/terraform-course

# AWS permissions 
  * Add User and Group on AWS account (EC2->Security Groups->search:default->Inbound rules->Add:CustomTCP,My IP)

# EC2 Instance
* ssh -i "ssh_key.pem" ec2-user@ec2-3-121-195-98.eu-central-1.compute.amazonaws.com
* install terraform
  * sudo yum install unzip
  * curl -O https://releases.hashicorp.com/terraform/0.12.13/terraform_0.12.13_linux_amd64.zip
  * sudo unzip terraform_0.12.13_linux_amd64.zip -d /usr/bin/
* git clone https:/github.com/wardviaene/terraform-course

# terraform
  * prepare instance.tf (use https://cloud-images.ubuntu.com/locator/ec2/ to find ami)
  * terraform init 
  * terraform apply
