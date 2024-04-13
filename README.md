# EKS-Terraform-Jenkins
EKS-Terraform-Jenkins

aws eks update-kubeconfig --region us-east-1 --name amonkincloud-cluster


# How to configure git on local machine (used gitbash for it)
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

eval "$(ssh-agent -s)"

ssh-add ~/.ssh/id_rsa

cat ~/.ssh/id_rsa.pub

Add the content of id_rsa.pub to github SSH keys which you'll find in settings. 

The below command will give output of successfull authentication
ssh -T git@github.com

