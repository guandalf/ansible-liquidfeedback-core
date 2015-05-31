liquidfeedback-core
===================

Ansible role to install [Liquid Feedback](http://liquidfeedback.org).

Requirements
------------

-

Role Variables
--------------

```
lf_home: /opt

lf_core_version: v3.0.4

lf_pg_db: liquid_feedback
lf_pg_user: lf_user
```

Dependencies
------------

* ANXS.PostgreSQL
* ANXS.monit

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

GPLv3

Author Information
------------------

[Jason McVetta](mailto:jason.mcvetta@gmail.com), Silicon Beach Heavy Industries
