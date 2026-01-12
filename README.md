

 Ansible Automation Project

This repository contains Ansible playbooks to automate Linux server configuration, software installation, and application deployment.

It is designed as a **real DevOps automation project** for cloud (AWS EC2 / Ubuntu / RHEL) and on-premise servers.

---

## 📌 What This Project Does

Using Ansible, this project can:

- Configure Linux servers
- Install packages (Nginx, Docker, Git, etc.)
- Manage users and permissions
- Deploy applications
- Configure services
- Perform server hardening
- Automate repetitive admin tasks
## 🧰 Tools & Technologies

- Ansible  
- Linux (Ubuntu, RHEL, Amazon Linux)  
- SSH  
- YAML  
- Git & GitHub  
- AWS EC2  

## 📋 Inventory Example

`inventory/hosts`

```ini
[web]
13.233.45.120

[db]
13.234.78.221

## ⚙️ ansible.cfg

```ini
[defaults]
inventory = inventory/hosts
remote_user = ubuntu
host_key_checking = False
private_key_file = kanha.pem

## ▶️ How to Run a Playbook

Example – Install Nginx on servers:

```bash
ansible-playbook playbooks/install_nginx.yml
Install Docker:

```bash
ansible-playbook playbooks/install_docker.ym-

## 🧪 Test Connection

```bash
ansible all -m ping
 ☁️ AWS EC2 Setup

1. Launch EC2 (Ubuntu / RHEL)
2. Allow port 22 in Security Group
3. Download `.pem` key
4. Add IP to inventory
5. Run playbooks
## 📌 Why This Project?

This project proves:

* Infrastructure automation skills
* Linux administration
* Cloud server management
* DevOps best practices
* Production-ready Ansible
## 👨‍💻 Author
**Kanha (Kanhaiya Tiwari)**
DevOps Engineer |
## ⭐ If you like this project, give it a star!
