Role Name
=========
edge
Add and enable microsoft edge  repository then install edge.

Requirements
------------

RHEL 8-9 x86_64 systems

Role Variables
--------------

gpgkey and base URL set in defaults/main.yml

Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      gather_facts: true
      become: true
      roles:
         - edge 

License
-------

BSD

Author Information
------------------

rmhzndo@ucl.ac.uk

