MIGRATION TO 2.X GUIDE

1.

ssh_users:
  - name: user1
    key: "{{ lookup('file', 'user1.pub') }}"



Common Ansible Role
=========

Creates user and installs some useful software

Requirements
------------

Newly created Ubuntu/Debian server.

Role Variables
--------------

login: username you want to login
login_key: path to your local public SSH key

Dependencies
------------

No dependencies

Example Playbook
----------------

Everything is very simple here

License
-------

BSD

Author Information
------------------

mail@grigor.io
