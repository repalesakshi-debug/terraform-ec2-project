# AWS EC2 Instance using Terraform

## 📌 Project Overview

This project demonstrates how to launch an **AWS EC2 instance using Terraform** with the help of **Data Sources and Terraform Modules**.

The project follows a modular structure to make the infrastructure reusable and easy to manage.

## 🛠️ Technologies Used

* Terraform
* Amazon Web Services (AWS)
* Amazon EC2
* Terraform Modules
* Terraform Data Sources
* Git & GitHub

## 📂 Project Structure

```text
terraform-ec2-project/
│
├── environments/
│   └── compute/
│       └── EC2/
│           └── dev/
│               ├── main.tf
│               ├── provider.tf
│               ├── variables.tf
│               ├── terraform.tfvars
│               └── output.tf
│
├── modules/
│   └── compute/
│       └── EC2/
│           ├── main.tf
│           ├── variables.tf
│           └── output.tf
│
├── screenshort/
│   └── ...
│
└── .gitignore
```

## ⚙️ How It Works

1. Terraform is configured with the AWS provider.
2. AWS Data Sources are used to retrieve existing AWS resources/information.
3. An EC2 instance is created using a reusable Terraform module.
4. Variables are passed from the development environment to the module.
5. Terraform outputs provide information about the created EC2 instance.

## 🚀 Terraform Commands

### Initialize Terraform

```bash
terraform init
```

### Validate Configuration

```bash
terraform validate
```

### Create Execution Plan

```bash
terraform plan
```

### Create EC2 Instance

```bash
terraform apply
```

### Destroy Infrastructure

```bash
terraform destroy
```

## 📸 Screenshots

Screenshots of the Terraform EC2 deployment are included in the `screenshort` folder.

## 🎯 Learning Outcomes

Through this project, I learned:

* Creating EC2 infrastructure using Terraform
* Using Terraform Data Sources
* Creating and using Terraform Modules
* Passing variables between environment and modules
* Managing AWS infrastructure as code
* Structuring Terraform projects
* Using Git and GitHub for version control

## 👩‍💻 Author

**Sakshi Repale**

Information Technology Engineering Student
Cloud Computing | AWS | Linux | Terraform | DevOps
