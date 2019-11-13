Magic Glass
===========

Deploy basic infrastructure via Ansible.

DEBUG bootstrap: 
```
ssh-copy-id -i secrets/ssh/glass-bootstrap user@target-host
ansible-playbook bootstrap.yml -i bootstrap -u root
```

DEBUG normal:
```
ansible-playbook site.yml -i inventory
