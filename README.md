Ansible role: Tailscale
=========

[![CI](https://github.com/xiple/ansible-role-tailscale/actions/workflows/ci.yml/badge.svg)](https://github.com/xiple/ansible-role-tailscale/actions/workflows/ci.yml)

An ansible role that installs tailscale on Linux.

Requirements
----------------

None.

Role Variables
----------------

```yaml
tailscale_ip_forwarding_enable: false
tailscale_sysctl_file: "/etc/sysctl.d/99-tailscale.conf"
```

Whether to enable ip forwarding for Tailscale exit-node feature.

Supported distributions
----------------

This role has been been developed and tested on the following distributions :

- Debian : 13
- Fedora : 44, 43

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
