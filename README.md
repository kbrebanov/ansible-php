[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

php
===

Installs PHP

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name        | Default | Description                            |
|-------------|---------|----------------------------------------|
| php_version | 5.6     | Version of PHP to install (5.5 or 5.6) |

Dependencies
------------

None

Example Playbook
----------------

Install latest version of PHP
```
- hosts: all
  roles:
    - { role: kbrebanov.php }
```

Install previous version of PHP
```
- hosts: all
  roles:
    - { role: kbrebanov.php, php_version: 5.5}
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
