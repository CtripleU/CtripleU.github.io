---
title: "Ansible Nginx Load Balancer Infrastructure"
date: 2021-10-06
author_profile: true
excerpt: "Building and deploying an Nginx load balancing infrastructure using Ansible and Vagrant."
tags: [ansible, nginx, load balancing, vagrant, devops]
header:
  image: "images/projects/load-balancer/lb.webp"
  teaser: "images/teasers/lb.avif"
mathjax: "true"
---


This project demonstrates the setup and deployment of an Nginx load balancing infrastructure using Ansible and Vagrant. It includes the creation of three virtual machines: one load balancer and two web servers, all configured and managed through Ansible playbooks.

## Tech Stack

- Vagrant
- VirtualBox
- Ansible
- Nginx
- Ubuntu 18.04 (Bionic)
- Python
- Flask

## Key Features

1. Automated VM provisioning with Vagrant
2. Configuration management using Ansible
3. Nginx load balancer setup
4. Deployment of a simple Flask application on web servers
5. Round-robin load balancing demonstration

## Project Structure

- `Vagrantfile`: Defines the virtual machine configurations
- `ansible/`:
  - `ansible.cfg`: Ansible configuration file
  - `hosts`: Inventory file for Ansible
  - `site.yml`: Main Ansible playbook
  - `playbook_nginx.yml`: Playbook for Nginx configuration
  - `playbook_web_servers.yml`: Playbook for web server setup
  - `nginx.cfg`: Nginx configuration file

## Setup and Deployment

1. Clone the repository
2. Ensure Vagrant, VirtualBox, and Ansible are installed
3. Run `vagrant up` to create and provision the VMs
4. The infrastructure will be automatically configured using Ansible playbooks

## Load Balancer Testing

- Access `http://192.168.33.11` in a web browser
- Refresh to see responses alternating between server-1 and server-2
- Alternatively, use `curl http://192.168.33.11` from the terminal

## Conclusion

This project showcases the power of infrastructure as code and configuration management in creating a scalable and easily reproducible load balancing setup. It provides hands-on experience with key DevOps tools and practices.

[View Project on GitHub](https://github.com/CtripleU/Ansible-Nginx-Load-Balancer-Infrastructure.git)