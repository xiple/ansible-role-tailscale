Ansible role: Tailscale
=========

[![CI](https://github.com/xiple/ansible-role-tailscale/actions/workflows/ci.yml/badge.svg)](https://github.com/xiple/ansible-role-tailscale/actions/workflows/ci.yml)

An ansible role that installs tailscale on Linux.

Requirements
----------------

None.

Role Variables
----------------

None.

Supported distributions
----------------

This role has been been developed and tested on the following distributions :

- Debian : 13
- Fedora : 43, 42

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - xiple.tailscale
```

License
-------

MIT
