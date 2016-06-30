Database
=========

This role will install Mysql and Redis and provide backups for Mysql to S3 server

Requirements
------------

TBD

Role Variables
--------------

db_name: 'name of mysql database'
db_user: 'name of mysql user for database'
db_password: 'password for mysql'

backup_dir: 'local path for mysql backups'
backup_hour: 'hour to make local backup'
backup_s3key: 'S3 backup key'
backup_s3secret: 'S3 backup secret'
backup_bucket: 'bucket to make backups'

Dependencies
------------

Commons role required

Example Playbook
----------------


License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
