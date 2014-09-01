Ansible Role -  Neo4j Server
============================

A Neo4j server role to install Neo4j server on elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


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
