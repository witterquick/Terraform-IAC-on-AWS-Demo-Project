# AWS EKS Cluster with Terraform

## Objectives: 
- Leveraging Terraform as Infrastructure-as-Code to provision a highly scalable AWS EKS Cluster.
- building an AWS VPC 3-Tier network with Terraform.
- building an AWS EKS Cluster with Public and Private Node Groups with Terraform.
- Implementing a Terraform Remote State Datasource.
- automating the AWS EBS CSI Controller installation process with Terraform.
- AWS EKS IAM Demo projects.
- implementing an AWS Load Balancer Controller Install on an AWS EKS Cluster with Terraform.
- Ingress Service Demos (AWS Application Load Balancer) using the Terraform Kubernetes Provider.
- Kubernetes Service Demos for AWS Load Balancer Controller.
- running all workloads of EKS Cluster on AWS Fargate (Fargate Only EKS Cluster).
- installing Kubernetes Cluster Autoscaler on an AWS EKS Cluster with Terraform.
- Setting up a Horizontal and Vertical Pod Autoscaler with Terraform.
- AWS EKS Monitoring and Logging using kubectl and Terraform

### Terraform Concepts in Use
- Terraform Input Variables
- Terraform Datasources
- Terraform Output Values
- Terraform Input Variable basics
  -    AWS Region
  -    Instance Type
  -    Key Name
- Defining Security Groups and Associate them as a List item to AWS EC2 Instance
  -    vpc-ssh
  -    vpc-web
- Terraform Output Values
  -    Public IP
  -    Public DNS
- Get latest EC2 AMI ID Using Terraform Datasources concept
- Use existing EC2 Key pair terraform-key
  - Key to be invalid after running demo practice successfully.
- Using all of the above to create an EC2 Instance in the default VPC

### Terraform Providers used
- AWS Terraform Provider
- Kubernetes Terraform Provider
- Kubectl Terraform Provider
- HTTP Terraform Provider
- Null Terraform Provider
- Helm Terraform Provider
