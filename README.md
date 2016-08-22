mamercad.zabbix-server
======================

Stands up Zabbix 3.0.0 (server) with MariaDB on RHEL/CentOS 7.x

Requirements
------------

- Fedora EPEL (for MySQL-python)

Role Variables
--------------

The password for the Zabbix database user can be set in vars/main.yml

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: zabbix
  roles:
    - mamercad.zabbix-server
```

License
-------

GPLv3

Author Information
------------------

Mark Mercado <mamercad@umflint.edu>
