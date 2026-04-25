# terraform-k8-workstation
Creating K8 Workstation using Terraform

# Commands

```shell
terraform init

terraform plan

terraform apply -auto-approve

have to wait till the EKS nodes created in AWS(can verify at EC2 level)

Once created do ssh to `roboshop-dev-workstation` and do authentication by below command

# Authenticate kubectl with the cluster
aws eks update-kubeconfig --region us-east-1 --name roboshop

kubectl get nodes
```