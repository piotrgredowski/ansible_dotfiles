# Ansible dotfiles

My simple dotfiles managed by ansible.

## Run

```bash
# all
ansible-playbook playbook.yml -i inventory/hosts.yml -v

# specific host
ansible-playbook playbook.yml -i inventory/hosts.yml -l specific-host -v
```
