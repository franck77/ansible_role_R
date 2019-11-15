
Description
=========

Install, config and remove Microsoft-R on a server

Requirements
------------

NA


Role Variables
--------------

You need to init this variables :

`
role_r_java_home
`


Dependencies
------------

NA

Example Playbook
----------------

```
- hosts: r
  tasks:
    - name: "Install & config R"
      include_role:
        name: "ansible_role_R"
      vars:
        state: "role_r_whole_install"
```

Author
------------------

Franck VIEIRA

