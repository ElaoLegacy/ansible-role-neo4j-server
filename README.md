WARNING: This role is no longer maintained !!!
==============================================

You are strongly encouraged to switch to the new roles stack on https://github.com/ElaoInfra
--------------------------------------------------------------------------------------------

By the way, this role will remain available on https://github.com/ElaoLegacy
----------------------------------------------------------------------------


Ansible Role -  Neo4j Server
============================

A Neo4j server role to install Neo4j server on elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


Role Handlers
-------------

    neo4j server restart  # Restart Neo4j server


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.neo4j-server }


License
-------

MIT


Author Information
------------------

http://www.elao.com/
