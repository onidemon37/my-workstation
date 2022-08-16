# my-workstation

- Repo to provision my workstation

Install requirements

```
pip install -r requirements.txt
```

- Run Playbook

```
# install everything
ansible-playbook -i inventory/hosts.ini playbook/myworkstation.yml --diff

# Install just oh-my-zsh
ansible-playbook -i inventory/hosts.ini playbook/oh-my-zsh.yml --diff

# Install libvirt only
ansible-playbook -i inventory/hosts.ini playbook/libvirt.yml --diff
```
