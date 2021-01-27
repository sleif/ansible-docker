sleif.docker
============

This role installs Docker with the help of geerlingguy.docker and configure it.

Requirements
------------

n/a

Role Variables
--------------

n/a

Dependencies
------------

Needs geerlingguy.docker to make sure Docker is available.

Example Playbook
----------------

    - hosts: "servers"
      roles:
        - { role: sleif.docker, tags: "docker" }

License
-------

MIT

Author Information
------------------

Created in 2021 by Sebastian Berthold
