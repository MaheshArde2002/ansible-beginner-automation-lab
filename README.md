# Ansible Beginner Automation Lab on Ubuntu

## About This Project

This is a beginner-level Ansible practical lab performed using Ubuntu Linux.

In this project, I installed Ansible on an Ubuntu server and configured it as an Ansible Controller. I connected another Ubuntu server as a Managed Node using SSH key-based authentication.

I also created an Ansible inventory file and basic playbooks to test connectivity and install Nginx on the managed server.

## Project Objectives

- Install Ansible on Ubuntu.
- Check the Ansible version.
- Test Ansible using the localhost ping command.
- Generate the Ansible configuration file.
- Understand the Ansible Controller and Managed Node setup.
- Configure SSH key-based authentication.
- Create and view an Ansible inventory.
- Create a basic ping playbook.
- Create and execute an Nginx installation playbook.
- Check the Nginx service status.

## Lab Environment

| Component | Details |
|---|---|
| Operating System | Ubuntu Linux |
| Automation Tool | Ansible |
| Controller Hostname | Ansible-Server |
| Controller IP | 172.31.30.186 |
| Managed Node | Server-1 |
| Managed Node IP | 172.31.21.182 |
| SSH User | ubuntu |
| Authentication | SSH Key-Based |

## Project Steps

### 1. Ansible Installation

Installed Ansible on Ubuntu using the package manager and Ansible PPA.

### 2. Ansible Version and Connectivity Testing

Verified the installation using:

```bash
ansible --version
```

Tested local connectivity:

```bash
ansible localhost -m ping
```

### 3. Ansible Configuration

Generated an Ansible configuration file using:

```bash
ansible-config init --disabled -t all > ansible.cfg
```

Reviewed the generated configuration and its default settings.

### 4. Controller and Managed Node Setup

Identified the hostnames and IP addresses of both Ubuntu servers.

Configured SSH key-based authentication from the controller to the managed node.

### 5. Inventory Configuration

Created and edited the Ansible hosts inventory file to define the managed server.

### 6. First Ansible Ping Playbook

Created a basic Ansible Playbook to test connectivity with the managed node.

### 7. Nginx Installation Playbook

Created an Ansible Playbook for installing Nginx on the managed node.

Executed the playbook and checked the Nginx service status.

## Project Results

- Ansible installed and verified.
- Localhost connectivity tested.
- Ansible configuration file generated.
- SSH key-based connection configured.
- Managed node added to the inventory.
- Basic ping playbook created and executed.
- Nginx installation playbook executed.
- Nginx service status checked.

## Screenshots

The `screenshots/` directory contains 15 screenshots documenting the installation, configuration, SSH setup, inventory management, playbook creation, and Nginx deployment.

## Technologies Used

- Ubuntu Linux
- Ansible
- SSH
- YAML
- Bash
- Nginx

## Author

Mahesh Arde

GitHub: https://github.com/MaheshArde2002

