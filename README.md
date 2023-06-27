# ACPC Control server ansible playbook
A repo contains the ansible playbook tree. The playbook contains of tasks and roles. The main task is found on the root control.yml. The control playbook runs only on localhost.

# Requirements:
  * Internet connection
  * Fresh ubuntu box installation
  * Downloading capability

# Installation
  * sudo apt update
  * sudo apt -y install python3-pip
  * sudo pip3 install ansible
  * mkdir ansible
  * cd ansible
  * git clone https://github.com/acpc-system/acpc-control-ansible

# Usage
  * cd acpc-control-ansible
  * sudo ansible-playbook control.yml
  * sudo systemctl reboot
