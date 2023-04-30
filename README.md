Ansible Role `matchbox`
=========

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/lstig/ansible-role-matchbox/blob/main/LICENSE)

Install and manage [matchbox](https://matchbox.psdn.io).

Requirements
------------

This role relies on filters in the `community.general` collection, specifically: `community.general.json_query`. Prior to running, ensure you have the following dependencies installed:

```sh
ansible-galaxy collection install community.general
pip install --user jmespath
```

Role Variables
--------------

[defaults](defaults/main.yml)

Dependencies
------------

None.

Example Playbook
----------------

```yaml
---
- hosts: servers
  roles:
    - role: lstig.matchbox
      become: yes
```
