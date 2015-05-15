php
===

Installs PHP

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name        | Default | Description                              |
|-------------|---------|------------------------------------------|
| php_version | 5.6     | Version PHP to install (5.4, 5.5 or 5.6) |

Dependencies
------------

None

Example Playbook
----------------

Install PHP
```
- hosts: all
  roles:
    - { role: kbrebanov.php }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
