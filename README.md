liquidfeedback_core
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

```yaml
- hosts: lf_core
  roles:
	 - siliconheavy.liquidfeedback_core
```

License
-------

GPLv3

Author Information
------------------

[Jason McVetta](mailto:jason.mcvetta@gmail.com), Silicon Beach Heavy Industries
