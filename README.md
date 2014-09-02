Ansible Role - PostgreSQL Server
================================

A PostgreSQL Server role to install PostgreSQL Server on elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


Role Handlers
-------------

    postgresql server restart  # Restart PostgreSQL server


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.postgresql-server }


License
-------

MIT


Author Information
------------------

http://www.elao.com/
