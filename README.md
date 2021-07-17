# Provision an EKS Cluster for requirement given on UpWork

[Upwork Job link](https://www.upwork.com/jobs/~01f6e89f44faab03d3)

Thanks for the source companion repo to the [Provision an EKS Cluster learn guide](https://learn.hashicorp.com/terraform/kubernetes/provision-eks-cluster), containing
Terraform configuration files to provision an EKS cluster on AWS.

Note: This repository created to help this UpWork job request and not earn any money unless job poster would like to fund this work.

# Job Title - EKA/RDS/EFS creation on AWS with Terraform

# Job summary: 

The need is to create an EKS Cluster into an existing VPC on AWS. The VPC on AWS has:

3 private subnets (this is where the control plane can run)
3 public subnets (this is where the workers will run)

The EKS cluster needs an EFS mount, so the EFS needs to be created by the terraform as well.

Lastly, I need a PostgreSQL instance to be deployed into two (2) of the AZ's in the private subnets with a db created. The db name is capsule8. A security group should be created for the EKS to reach the RDS instance.