# ansible-playbooks
Automating the boring stuff


### Running centos-setup.yaml

- create a roles folder in the same path as the yaml file and clone the ansible-role-nvm - https://github.com/morgangraphics/ansible-role-nvm

- run the playbook - ansible-playbook centos-setup.yaml -u root
- ensure you ve added the right host in /etc/ansible/hosts - in my case [web]

