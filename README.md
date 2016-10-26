list-backups
============

List previous backups.

Requirements
------------

This role requires Ansible 1.5 or higher, and platform requirements are listed in the metadata file.

Role Variables
--------------

The variables that can be passed to this role and a brief description about them are as follows.

	backup_dir:


Dependencies
------------

None

Example Playbook
----------------

List previous backups:

    - hosts: servers
      roles:
        - role: quekky.list-backups
		  backup_dir: /backup


License
-------

MIT

Author Information
------------------

quekky
