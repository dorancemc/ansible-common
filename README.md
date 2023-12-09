Role Name
=========

Role to run common tasks when deploy the host for the first time

Requirements
------------


Role Variables
--------------

Check the file defaults/main.yml to set variables

Example Playbook
----------------

```yaml
- hosts: all
  vars:
    common_hosts:
      server.example.com: 172.2.1.9
  roles:
    - { role: dorancemc-ansible-common, tags: [ common ] }

```

License
-------

[Apache-2.0](https://github.com/robertdebock/ansible-role-bootstrap/blob/master/LICENSE).

Author Information
------------------

  Dorance Martinez 
