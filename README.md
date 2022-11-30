
**Case study**
[Website]()

## List all hosts targeted
[servers]
server1 ansible_host=10.0.2.15

## provid the passwords
[all:vars]
ansible_python_interpreter=/usr/bin/python3
ansible_user=pass
ansible_password=pass
ansible_become_pass=pass





**Overview**


**Initials configuration**


1. hosts config
In hots file of your ansible home, list the targeted machine and update the passwords

[servers]
server1 ansible_host=X.X.X.X

[all:vars]
ansible_python_interpreter=/usr/bin/python3
ansible_become_pass=pass

2. roles config
 a. copy the Role-server file in ansible home
 b. copy apache-tomcat-setup-role and maven-setup-role in sub directory roles of ansible




**How run**
 on your temrminal type > ansible-playbook role-server.yml


**Tech Stack**


**API**


