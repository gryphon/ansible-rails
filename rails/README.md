Rails role
=========

Frontend server for Ruby on Rails with rbenv, puma and nginx. Nodejs used for some background.

Requirements
------------

Common role from gryphon

Role Variables
--------------

user: 'deploy username for capistrano'
home: '/home/{{ user }}'
name: 'application name'
application: '{{ home }}/web/{{ name }}'
ruby_version: '2.2.3'
rbenv_root: '{{ home }}/.rbenv'
nodejs_branch: "node_4.x"
nodejs_apt_state: "latest"

Dependencies
------------


Example Playbook
----------------

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
