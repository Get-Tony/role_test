Common
=========

This role is used to install common packages and configure common settings on all servers.

Requirements
------------

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):
  
      common_packages

Dependencies
------------

None.

Example Playbook
----------------

    - name: Apply common configuration to all servers
      hosts: managed
      roles:
         - common

License
-------

All rights reserved.

Author Information
------------------

This role was created in 2022 by Anthony Pagan.
