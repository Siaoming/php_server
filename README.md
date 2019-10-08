Role Name
=========

A demo role for deploy PHP server.

Requirements
------------

No special requirement for Ansible runtime.

Role Variables
--------------

No settable variables available for now.

Dependencies
------------

siaoming.httpd_server role.

Example Playbook
----------------

    - hosts: servers
      roles:
      - { role: siaoming.php_server }

License
-------

Apache

Author Information
------------------

Siaoming
i@siaoming.cc
