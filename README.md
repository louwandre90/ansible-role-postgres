ansible-role-postgres
=========

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
         - { role: louwandre90.ansible-role-postgres }

License
-------

BSD

Author Information
------------------

This role was created in 2016 by Andre Louw.
