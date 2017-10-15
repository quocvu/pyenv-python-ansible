[![Build Status](https://img.shields.io/travis/quocvu/pyenv-python-ansible.svg)](https://travis-ci.org/quocvu/pyenv-python-ansible)

pyenv-python
================

A role to install pyenv, which is used to install multiple versions of
Python allowing you to select the appropriate version for your project

Requirements
------------

Ansible and an internet connection


Role Variables
--------------

* `python_versions` a list of python versions to install

Dependencies
------------

None

Example Playbook
----------------

To install pyenv, add the following in your playbook:

```
- hosts: servers
  roles:
    - { role: quocvu.pyenv-python }
```

License
-------

MIT

Author Information
------------------

Quoc Vu  

* https://linkedin.com/in/quocvu  
* https://github.com/quocvu
