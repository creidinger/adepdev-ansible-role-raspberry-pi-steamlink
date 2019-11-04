# Steamlink setup for Raspberry Pi
This script Automates the setup for steamlink on a raspberrypi.

---
## Requirements
1. Mac or Linux OS (have not texted on Windows, that will come in future)
1. Python
1. Ansible
1. SSH enabled Raspberry Pi

---
## Provisioning (running the script)
After initial config of PI (change default password and enable ssh)...
1. update the IP address of the PI in the ansible/inventories folder
1. `cd ansible`
1. `ansible-playbook -i inventories/hosts -u pi config_pi.yml`
