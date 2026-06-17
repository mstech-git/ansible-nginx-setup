# ansible-nginx-setup ⚙️

Automate Nginx web server installation and configuration on Ubuntu using Ansible.

### Tech Stack
Ansible, Nginx, Ubuntu, YAML, Configuration Management

### What This Does
1. Updates apt cache
2. Installs Nginx
3. Starts & enables Nginx service on boot
4. Deploys a custom index.html page

### How to Run
```bash
ansible-playbook -i inventory.ini playbook.yml
