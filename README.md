Debian-Supervisor
=================

Supervisor is a client/server system that allows its users to monitor and control a number of processes on UNIX-like operating systems.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-supervisor }

Tasks
-----

  - Install [supervisor](http://supervisord.org/) tool

License
-------

BSD