# ansible-playbook-template

# use case

## role install
```
git clone https://github.com/shase/ansible-playbook-template.git
cd ansible-playbook-template
ansible-galaxy install -f -r requirements.yml --roles-path=./roles
```

## execute playbook
```
ansible-playbook jenkins_servers.yml -i inventory/hosts
```
