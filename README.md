# 🏗️ Terraform + Ansible

Infrastructure as Code for the home lab.
This repository documents the full provisioning and configuration
management of all home lab services using Terraform and Ansible.

## 🖥️ Infrastructure

| Role | Device | Specs |
|---|---|---|
| Server | ASUS ROG Strix | Intel i7 · 16GB RAM · 256GB SSD + 1TB HDD |
| Workstation | ASUS Professional | AMD Ryzen 9 · 32GB RAM |

## 🛠️ Stack

- **Provisioning:** Terraform
- **Configuration Management:** Ansible
- **OS:** Ubuntu Server 24.04 LTS
- **Version Control:** Git + GitHub

## ✅ Roadmap

- [ ] Ansible installation and configuration on workstation
- [ ] First playbook — automated Ubuntu Server base setup
- [ ] SSH hardening playbook
- [ ] Fail2ban and UFW playbook
- [ ] Prometheus + Grafana deployment playbook
- [ ] Terraform installation and configuration
- [ ] Terraform state management setup
- [ ] Full homelab reprovisioning from scratch in one command

## 💡 Goal

If the server breaks or needs to be rebuilt from scratch,
a single command should reproduce the entire environment exactly as it was.
No manual steps. No forgotten configurations.

## 📐 Architecture

*Diagram coming soon*

## 📚 Documentation

Each step is documented as it is completed.
All Terraform and Ansible files are included in this repository.
