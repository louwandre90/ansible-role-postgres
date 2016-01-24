ansible-role-postgres
=========
[![Travis](https://img.shields.io/travis/rust-lang/rust.svg?style=flat-square)](https://travis-ci.org/louwandre90/ansible-role-postgres)
[![Ansible Role](https://img.shields.io/ansible/role/3078.svg?style=flat-square)](https://galaxy.ansible.com/detail#/role/7181)

This role installs the latest versions of the following postgres packages:

* postgresql
* postgresql-server-dev-all
* python-psycopg2

Packages are installed via apt and no configuration is done after installation. 

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: louwandre90.postgres }

License
-------

BSD

Author Information
------------------

This role was created in 2016 by Andre Louw.
