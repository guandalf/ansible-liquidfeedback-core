liquidfeedback_core
===================

Ansible role to install [Liquid Feedback
Core](http://dev.liquidfeedback.org/trac/lf/wiki/Core)


Role Variables
--------------

```yaml
lf_home: /opt

lf_core_version: v3.0.4
# How often, in minutes, to run lf_update and friends
lf_core_update_freq: 5

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
