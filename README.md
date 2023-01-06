# nhs-spineii-vm-setup
Ansible playbook to set up vm with my configuration

This playbook will install oh-my-zsh and two very nice plugins (auto complete and syntax highlighting)
If you would like to make changes to the zsh config please update `zsh/.zshrc` before running.

This playbook will also create ssh key pair for you to use with github and will helpfully print the pub key in the terminal.
You will then be able to configure your git config with your name "Your Name" and email address "your.email1@address.net"

The playbook will also pull the NCRS repository if not already done.

To run:
```bash
$ ansible-playbook main.yml
```
