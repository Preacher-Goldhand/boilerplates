# Boilerplates for Ansible, Terraform and Shell Scripts

## Overview
This repository contains a collection of Ansible playbooks and Terraform scripts designed to automate various tasks and configurations. It serves as a central resource for deploying and managing different applications, infrastructure, and services efficiently across diverse environments.

## Features
- **Modular Templates:** Predefined templates and scripts for a variety of use cases, including Kubernetes, database setups, infrastructure provisioning, and system configurations.
- **Customizable Playbooks and Scripts:** Easily adjustable to meet specific deployment requirements.
- **Idempotent Execution:** Ensures consistent results even when run multiple times.
- **Multi-Platform Support:** Compatible with popular Linux distributions and major cloud providers.

## Repository Structure

**Note:** Please maintain this structure.

```
.
├── ansible/                # Directory for Ansible-related resources
│   ├── playbooks/          # Directory containing Ansible playbooks
├── terraform/              # Directory for Terraform-related resources
│   ├── modules/            # Reusable Terraform modules
│   └── examples/           # Example configurations for infrastructure setups
|── shell-scripts/          # Directory containing various shell scripts 
├── README.md               # Documentation
```

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Preacher-Goldhand/boilerplates.git
cd boilerplates
```

### 2. Choose a Template or Script
- Browse the `ansible/` directory for Ansible templates.
- Browse the `terraform/` directory for Terraform scripts and modules.
- Browse the `shell-scripts/` directory for reusable shell scripts.

### 3. Run a Playbook or Apply Terraform
- **Ansible:**
  ```bash
  ansible-playbook -i inventory ansible/playbooks/<playbook-name>.yml
  ```
- **Terraform:**
  ```bash
  cd terraform/examples/<example-setup>
  terraform init
  terraform apply
  ```
# Ansible and Terraform Templates Repository

## Overview
This repository contains a collection of Ansible playbooks and Terraform scripts designed to automate various tasks and configurations. It serves as a central resource for deploying and managing different applications, infrastructure, and services efficiently across diverse environments.

## Features
- **Modular Templates:** Predefined templates and scripts for a variety of use cases, including Kubernetes, database setups, infrastructure provisioning, and system configurations.
- **Customizable Playbooks and Scripts:** Easily adjustable to meet specific deployment requirements.
- **Idempotent Execution:** Ensures consistent results even when run multiple times.
- **Multi-Platform Support:** Compatible with popular Linux distributions and major cloud providers.

## Repository Structure
```
.
├── ansible/                # Directory for Ansible-related resources
│   ├── playbooks/          # Directory containing Ansible playbooks
├── terraform/              # Directory for Terraform-related resources
│   ├── modules/            # Reusable Terraform modules
│   └── examples/           # Example configurations for infrastructure setups
|── shell-scripts/          # Directory containing various shell scripts 
├── README.md               # Documentation
```

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Preacher-Goldhand/boilerplates.git
cd boilerplates
```

### 2. Choose a Template or Script
- Browse the `ansible/` directory for Ansible templates.
- Browse the `terraform/` directory for Terraform scripts and modules.

### 3. Customize Variables
- For Ansible: Edit the `vars/main.yml` file or create a new variables file to suit your needs.
- For Terraform: Update the variable files in the `examples/` directory or pass variables directly via the CLI.

**Note:** Ensure that all required fields, such as IP addresses, hostnames, and sensitive variables, are filled in with actual values relevant to your environment.

### 4. Run a Playbook or Apply Terraform
- **Ansible:**
  ```bash
  ansible-playbook -i inventory ansible/playbooks/<playbook-name>.yml
  ```
- **Terraform:**
  ```bash
  cd terraform/examples/<example-setup>
  terraform init
  terraform apply
  ```
  - **Shell Scripts:**
  ```bash
  bash shell-scripts/<script-name>.sh

  ```
**Note:** Ensure that all required fields, such as IP addresses, hostnames, and sensitive variables, are filled in with actual values relevant to your environment.


## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
