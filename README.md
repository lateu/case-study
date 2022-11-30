
## Case study
[Website]()


## Overview
Rashford assoc. are having trouble provisioning their server environmentbecause of the inconsistencies caused by the new update. They have Hired Marcus to solve their problems related to managing servers. Marcus, after researching, introduced Ansible to the system. Now, he needs to provision the production environment for the upcoming update of their software.

**Action Items**
  1. Create separate roles for setting up Apache Tomcat and Apache Maven
  2. Add the necessary logic to the roles to set up the tools
  3. Create a new playbook and call Tomcat as well as Maven roles inside it
  4. Execute the playbook on all the hosts


**Initials configuration**


1. hosts config
  In hots file of your ansible home, list the targeted machine and update the passwords

*[servers]*
server1 ansible_host=X.X.X.X

*[all:vars]*
ansible_python_interpreter=/usr/bin/python3
ansible_become_pass=pass

2. roles config

   a. copy the Role-server file in ansible home.
 
   b. copy apache-tomcat-setup-role and maven-setup-role in sub directory roles of ansible.


## How to run

 open your temrminal type > ansible-playbook role-server.yml


## Tech Stack

## Todo




