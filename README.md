#### Personal Ansible Playbook

For quickly setting up development environment on a fresh Ubuntu 22 minimal install.

```
sudo apt-get install python3 ansible git
git clone git@github.com:iimez/ansible-dev-setup.git
ansible-playbook main.yml -K
```