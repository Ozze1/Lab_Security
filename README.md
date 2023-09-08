# Lab_Security

Setting Up Security, Prometheus, and Grafana with Ansible

Introduction
This lab focuses on security and monitoring using Ansible with different playbooks. The goal is to set up a virtual machine (VM) on Hetzner secure it, and install Prometheus and Grafana. The lab tasks are as follows:

Create a VM on Hetzner (CX11) using cloud-config and avoid SSHing in as root.
Upgrade all packages on the VM to the latest available versions.
Enable the firewall, allowing only necessary ports.
Enhance SSH security by following best practices.
Install Prometheus and Grafana.
Configure Prometheus and Grafana to listen only on localhost (127.0.0.1).
Set up a Caddy reverse proxy with TLS to access Prometheus and Grafana.
All tasks should be automated using an Ansible playbook.
