lihas_hosts
=========

add/reßplace entries in /etc/hosts

Requirements
------------

-

Role Variables
--------------

```
hostentries.{}
%.config.hostentries.{}
```

Dependencies
------------

* lihas_variables

```
ansible-galaxy install -r requirements.yml
```

Example Playbook
----------------

```
---
- hosts: '*'
  role: lihas_hosts
...
```

License
-------

GPLv3

Author Information
------------------

Adrian Reyer, https://lihas.de/
