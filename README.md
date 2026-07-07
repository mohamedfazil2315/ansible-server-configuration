# Ansible Server Configuration

Production-ready Ansible project for configuring Ubuntu servers.

## Features

- Inventory management
- Common server bootstrap
- Docker installation
- Nginx installation
- Idempotent playbooks

## Structure

```
inventory/
playbooks/
roles/
  common/
  docker/
  nginx/
ansible.cfg
```

## Run

```bash
ansible-playbook playbooks/site.yml
```

## Requirements

- Ansible 2.12+
- Ubuntu 22.04+
- SSH access with sudo
