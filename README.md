Users
=========

Ansible role to create users

Requirements
------------

Need ansible 2+

Role Variables
--------------

```yaml
users:
- www:
  name: "www"
  comment: "www user"
  createhome: "yes"
  home: "/home/www"
  shell: "/bin/false"
```

Dependencies
------------

There is no dependency.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - role: SimpliField.users
```

License
-------

BSD
