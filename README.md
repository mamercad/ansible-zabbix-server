mamercad.zabbix-server
=========

Stands up Zabbix 3.0.0 (server) with MariaDB on RHEL/CentOS

Requirements
------------

None

Role Variables
--------------

The password for the zabbix database user can be set in vars/main.yml

Dependencies
------------

None

Example Playbook
----------------

    - hosts: zabbix-server
      roles:
         - mamercad.zabbix-server

License
-------

GPLv3

Author Information
------------------

Mark Mercado <mamercad@umflint.edu>

