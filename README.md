Ansible / rethinkdb
====================

Ansible playbook to setup a RethinkDB with a master and slave.



Usage
-----

Create an inventory file with the servers that you want to Node.js on or use `$ANSIBLE_HOSTS`.

if connecting with root:

    ansible-playbook -i inventory-file -u root main.yml

if sudoing:

    ansible-playbook -i inventory-file -K main.yml



Ansible
-------

Not sure what Ansible is? Read the getting started here: http://procbits.com/2013/09/08/getting-started-with-ansible-digital-ocean


RethinkDB
---------

Read docs here: http://www.rethinkdb.com/docs/



Todo
----

- make OS agnostic
- different types (single master, multiple slaves, etc) of configurations



Other RethinkDB playbooks
-------------------------

- https://github.com/nimajalali/ansible-rethinkdb



License
-------

MIT/X11, Copyright 2013, JP Richardson