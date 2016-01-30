sysdig
======

[![Build Status](https://travis-ci.org/kbrebanov/ansible-sysdig.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-sysdig)

Installs sysdig.

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name           | Default | Description                  |
|----------------|---------|------------------------------|
| sysdig_version | 0.6.0   | Version of Sysdig to install |

Dependencies
------------

  - kbrebanov.dkms

Example Playbook
----------------

Install sysdig
```
- hosts: all
  roles:
    - { role: sysdig }
```

Install sysdig specifying a version
```
- hosts: all
  roles:
    - { role: sysdig, sysdig_version: 0.1.98 }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
