# Lab_Security

Setting Up Security, Prometheus, and Grafana with Ansible

Introduction
This lab focuses on security and monitoring using Ansible with different playbooks. The goal is to set up a virtual machine (VM) on Hetzner secure it, and install Prometheus and Grafana. The lab tasks are as follows:

1. Create a VM on Hetzner (CX11) using cloud-config and avoid SSHing in as root.

2. Upgrade all packages on the VM to the latest available versions.

3. Enable the firewall, allowing only necessary ports.

4. Enhance SSH security by following best practices.

5. Install Prometheus and Grafana.

6. Configure Prometheus and Grafana to listen only on localhost (127.0.0.1).

7. Set up a Caddy reverse proxy with TLS to access Prometheus and Grafana.

8. All tasks should be automated using an Ansible playbook.
