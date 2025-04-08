# AI-Terraform-AzureVM-demo

# 🚀 Deploy Azure VM Using Terraform + AI Assistance

This project shows how to use AI (like ChatGPT or GitHub Copilot) to generate Terraform code and deploy a **Virtual Machine on Microsoft Azure** — in under 3 minutes!

🎥 [Watch the YouTube Video Here](#) *((https://youtube.com/shorts/Y87SQnN_NhM))*

---

## 🔧 Tools & Technologies Used

- **Terraform** – Infrastructure as Code (IaC) tool
- **Microsoft Azure** – Cloud provider
- **Mistral/Ollama** – AI assistant to write and explain Terraform code
- **Azure CLI** – To authenticate and manage Azure resources
- **VS Code** – As the code editor

---

## 📁 Project Structure

```bash
AI-Terraform-AzureVM-demo/
├── main.tf              # Main Terraform configuration file
├── variables.tf         # Input variables
├── outputs.tf           # Output values
├── provider.tf          # Azure provider config
└── README.md            # Project documentation


Prerequisites
Make sure the following tools are installed:

Terraform

Azure CLI

VS Code

Azure subscription

AI-Generated Code
The Terraform configuration files were generated using AI suggestions from Mistral. Prompts used

ollama run mistral "Generate complete Terraform code using only plain resource blocks (no modules) to create a basic Ubuntu 20.04 virtual machine in Azure.

Include the following Azure resources:
- Resource Group
- Virtual Network
- Subnet
- Public IP
- Network Interface
- Linux Virtual Machine (with SSH key authentication)

Use these default values:
- Location: westeurope
- VM size: Standard_B1s
- VM name: myUbuntuVM
- Admin username: azureuser
- SSH public key path: ~/.ssh/id_rsa.pub

Do NOT use any external or local modules. Write all the code explicitly using Terraform's azurerm provider resources.

Split the code into:
- main.tf
- variables.tf
- outputs.tf

Ensure the code is ready to run locally using terraform init,plan and apply without any additional dependencies or module references."

🚀 How to Deploy
1. Login to Azure
az login

2. Initialize Terraform
terraform init

3. Preview the Deployment
terraform plan

4. Apply the Configuration
terraform apply
Type yes when prompted.

5. Destroy the Resources
To clean up and avoid charges:

terraform destroy

📺 Watch the Tutorial
👉 YouTube: Use AI to Write Terraform Code & Deploy Azure VM FAST (https://youtube.com/shorts/Y87SQnN_NhM)

📬 Stay Connected
YouTube: LearnWithDevOpsEngineer3682




