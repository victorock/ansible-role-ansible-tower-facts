Ansible Tower Setup
=========

Simple Role to Gather Facts from Ansible Tower by Red Hat.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
- name: "Gather Facts from Ansible Tower by Red Hat"
  hosts: tower

  roles:
    - victorock.ansible-tower-facts
```

License
-------

GPLv3

Author Information
------------------

Victor da Costa
