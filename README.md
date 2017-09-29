# ansible-playbook-template

Please customize it for use

# change install version

edit this vars [group_vars/jenkins.yml](https://github.com/shase/ansible-playbook-template/blob/master/group_vars/jenkins.yml#L2)

# use case (example)

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

## test
```
curl 127.0.0.1:8080
```
