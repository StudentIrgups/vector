Role Name
=========

Role to deploy vector on remote VM.

Requirements
------------

Ubuntu 2204.

Role Variables
--------------

defaults/main.yml 
  - vector_version - version of vector
vars/main.yml
  - vector_config_path - path to keep config of vector

Dependencies
------------

Nope

Example Playbook
----------------

```

- name: Install Vector
  hosts: vector
  roles: 
    - vector
  tags:
    - vector
```

License
-------

MIT

Author Information
------------------

by Alex Beznosov for Netolgy
