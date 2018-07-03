Ansible Tower Facts
=========

Simple Role to Gather Facts from Ansible Tower by Red Hat through REST.

Dependencies
------------

None

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
    - role: victorock.tower_facts
      autorun: yes
      tower_config:
        host: "localhost"
        username: "admin"
        password: "password"
        verify_ssl: false
        format: json

  tasks:
    - debug: var=tower_facts

```

License
-------

GPLv3

Author Information
------------------

Victor da Costa
