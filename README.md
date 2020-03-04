# iac-azure-aks-tf-k8s
Infrastructure as code: Provisioning an AKS cluster using Terraform on Azure.
# iac-azure-aks-tf-k8s 

# Infrastructure as code: Provisioning an AKS cluster using Terraform on Azure.




-----

## Introduction: 

**Azure Kubernetes Service (AKS)** manages your hosted Kubernetes environment.AKS allows you to deploy and manage containerized applications without container orchestration expertise. AKS also enables you to do many common maintenance operations without taking your app offline. These operations include provisioning, upgrading, and scaling resources on demand.

> 💡By using **Terraform** to provision AKS Kubernetes clusters you can begin to both automate, but also now that you have captured it as a codified form, you can check it into version control and you get versioning.

-----

The following will help you to perform the tasks:

* Use Terraform and AKS to create a Kubernetes cluster
* Use the kubectl tool to test the availability of a Kubernetes cluster

To create your Terraform-provisioned AKS cluster, please follow the following steps:

* Step1: Obtain the application source code
* Step2: Define an AKS Kubernetes cluster with Terraform
* Step3: Set up Azure storage to store Terraform state
* Step4: Create the Kubernetes cluster
* Step5: Test the Kubernetes cluster
* Step6: Monitoring and logs

-----

## Getting started

* The first step is to obtain the source code from Github.
```
git clone https://github.com/dhillonsiddharth/iac-azure-aks-tf-k8s.git
cd iac-azure-aks-tf-k8s

```
* Set up Azure storage to store Terraform state
* Create the Kubernetes cluster

````
terraform init
terraform validate
terraform plan
terraform apply
`````


