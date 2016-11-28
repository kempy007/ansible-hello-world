# Ansible Hello World

First steps/experiments with Ansible

## Setup

1. [Install Python](https://wiki.python.org/moin/BeginnersGuide/Download) 2.7.x
1. [Install Ansible](https://docs.ansible.com/ansible/intro_installation.html) 2.2.x

## Run

Ping all hosts in inventory file

```bash
ansible all -i hosts -m ping
```

Run playbook: ping localhost

```bash
ansible-playbook -i hosts hello.yml
```
