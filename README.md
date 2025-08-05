# homelab-infra
Repo for automation training on my homelab

## 📁 Project Structure

```
homelab-infra/
├── README.md
├── main.tf
├── variables.tf
├── terraform.tfvars
├── outputs.tf
├── providers/
│   └── proxmox.tf
├── modules/
│   └── ubuntu-vm/
│       ├── main.tf
│       ├── variables.tf
│       ├── outputs.tf
├── ansible/
│   ├── inventory.ini
│   ├── playbooks/
│   │   └── setup.yml
│   └── roles/
│       └── common/
│           ├── tasks/
│           │   └── main.yml
│           └── handlers/
│               └── main.yml
├── lima/
│   ├── Dockerfile (optional, if containerizing tools inside Lima)
│   ├── setup.sh (bootstraps Terraform, Ansible, Git, etc.)
│   └── notes.md (usage tips, Lima quirks, etc.)
└── .gitignore
```
