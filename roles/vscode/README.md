Role Name
=========

Add and enable microsoft vscode repository then install vscode.

Requirements
------------

RHEL 8-9 x86_64 systems

Role Variables
--------------

gpgkey and base URL set in defaults/main.yml

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    - hosts: servers
      gather_facts: true
      become: true
      roles:
         - vscode

License
-------

BSD

Author Information
------------------

rmhzndo@ucl.ac.uk
