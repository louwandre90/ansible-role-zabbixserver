ansible-role-zabbixServer
=========
[![Ansible Role](https://img.shields.io/badge/role-louwandre90.zabbixServer-blue.svg?style=flat-square)](https://galaxy.ansible.com/louwandre90/zabbixServer/)

This role installs Zabbix Server on Debian.


Requirements
------------

None

Role Variables
--------------

The following defaults are set:

    username: jarvis

To pass different variables:

    ansible-playbook playbook.yml -e 'username=myuser'
    
Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: louwandre90.zabbixServer }

License
-------

BSD

Author Information
------------------

This role was created in 2016 by Andre Louw.
