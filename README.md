# Just notes for myself on Ansible

## Format for keeping hosts in inventory file
```
samplehost ansible_host=192.168.88.1 ansible_user=sammy
samplehost2 ansible_host=192.168.88.2 ansible_user=sammy
```

## Basic commands to run playbooks
Just run the playbook against hosts in the inventory file:
```
ansible-playbook playbook_name.yml
```

Run the playbook against the specific host:
```
ansible-playbook playbook_name.yml -i 192.168.88.254, -u username
```

