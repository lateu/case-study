## List all hosts targeted
[servers]
server1 ansible_host=10.0.2.15

## provid the passwords
[all:vars]
ansible_python_interpreter=/usr/bin/python3
ansible_user=pass
ansible_password=pass
ansible_become_pass=pass
