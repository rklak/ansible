# Ansible playbook

All things to setup a new machine for local development

## Prepare

Install all roles and collections

```bash
ansible-galaxy install -r requirements.yml
```

## Run

Locally with become privilege

```bash
ansible-playbook -bK local.yml
```
