
Install htop [![Build Status](https://travis-ci.org/shengyou/ansible-role-htop.svg?branch=master)](https://travis-ci.org/shengyou/ansible-role-htop)
=========

install htop.

* Ubuntu 14.04, 16.04
* CentOS 6, 7

Requirements
------------

* ansible >= 2.3
* python >= 2.6

Role Variables
--------------

none.


Dependencies
------------

none.

Example Playbook
----------------

```
- name: install_htop.yml
  hosts: myhost
  gather_facts: yes
  become: yes

  roles:
    - install_htop
```

License
-------

MIT
