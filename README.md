# jenkins

A simple Ansible role for installing jenkins for RHEL/CentOS 7 and Debian 10.

- Install the necessary packages;

Requirements 
------------

The SELinux and firewall settings are not considered to be a concern of this role.

Role Variables []
--------------

Dependencies
------------

You need to install python-apt package on debian 10 


Example Playbook
----------------
```yml
---
- hosts: redhat,debian
  become: yes
  roles:

    - /path/jenkins
...
```

Example inventory
-----------------
```yml
[redhat]

node_redhat

[debian]

node_debian

```

Attention
---------

After running ansible you will see the temporary password and IP and port to complete the installation of jenkins.

## Contributing

Issues, feature requests, ideas are appreciated and can be posted in the Issues section.


Author Information
------------------
LinkedIn: https://br.linkedin.com/in/almircandido
