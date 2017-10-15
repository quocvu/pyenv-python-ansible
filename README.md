[![Build Status](https://img.shields.io/travis/quocvu/python-archlinux-ansible.svg)](https://travis-ci.org/quocvu/python-archlinux-ansible)
[![Ansible Role](https://img.shields.io/ansible/role/20520.svg)](https://galaxy.ansible.com/quocvu/python-archlinux)

python-archlinux
================

A role to instal Python and Python's goodies into an ArchLinux host.
That include python3, virtualenv, pip, and setuptools.
Optionally install the same set for python2

Requirements
------------

Ansible and an internet connection


Role Variables
--------------

* `install_python2` whether to install Python version 2 (true/false)
* `python_default_version` set the default version of python (python3 or python2)
* `python2_modules` list of modules to install with python2
* `python3_modules` list of modules to install with python3
* `python2_popular_modules` list of popular modules to install with python2
* `python3_popular_modules` list of popular modules to install with python3

Dependencies
------------

None

Example Playbook
----------------

To install Python and its tools, add the following in your playbook:

```
- hosts: servers
  roles:
    - { role: quocvu.python-archlinux }
```

License
-------

MIT

Author Information
------------------

Quoc Vu  

* https://linkedin.com/in/quocvu  
* https://github.com/quocvu
