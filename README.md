
## Case study
[Website]()


## Overview


**Initials configuration**


1. hosts config
  In hots file of your ansible home, list the targeted machine and update the passwords

*[servers]*
server1 ansible_host=X.X.X.X

*[all:vars]*
ansible_python_interpreter=/usr/bin/python3
ansible_become_pass=pass

2. roles config
 A. copy the Role-server file in ansible home.
 B. copy apache-tomcat-setup-role and maven-setup-role in sub directory roles of ansible.




## How to run

 open your temrminal type > ansible-playbook role-server.yml


## Tech Stack

## Todo




