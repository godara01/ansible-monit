# ansible-monit
[![Build Status](https://travis-ci.org/jimbydamonk/ansible-monit.svg?branch=master)](https://travis-ci.org/jimbydamonk/ansible-monit)

Install and configure monit.

Requirements
------------

NA

Role Variables
--------------

The default variables for this role are listed below. They are defined in defaults/main.yml`.

```yml
---
---
monit_conf_dir: /etc/monit.d
monit_templates_files: []
```

Dependencies
------------

None

Example Playbook
----------------

Simple Playbook:

    - hosts: servers
      roles:
        - ansible-monit


License
-------

Apache

Author Information
------------------
Mike Buzzetti
