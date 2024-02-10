Ansible Role `matchbox`
=========

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/lstig/ansible-role-matchbox/blob/main/LICENSE)

Install and manage [matchbox](https://matchbox.psdn.io).

Requirements
------------

- `gnupg2` should be installed working on the remote machine (it can be installed with the `lstig.gpg` role).
- `community.general.json_query` should be available on your controller ( part of the `community.general` collection).
- `jmespath` in order to use the `json_query` on your controller:

```sh
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
