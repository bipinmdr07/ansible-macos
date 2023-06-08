## Ansible Orchestration
An orchestration of development environment setup (Pop!_os)

#### Pre-requisites
- [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-and-upgrading-ansible)
- [OpenSSH Server](https://ubuntu.com/server/docs/service-openssh)

#### Usage
```shell
git clone https://github.com/bipinmdr07/ansible-macos.git

ansible-playbook -i inventory site.yml --ask-become-pass
```
