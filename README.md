Ansible Role `matchbox`
=========

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/lstig/ansible-role-matchbox/blob/main/LICENSE)

Install and manage [matchbox](https://matchbox.psdn.io).

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

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
```
