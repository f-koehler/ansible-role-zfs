# Ansible Role: archzfs

[![CI](https://github.com/f-koehler/ansible-role-zfs/workflows/CI/badge.svg?event=push)](https://github.com/f-koehler/ansible-role-zfs/actions?query=workflow%3ACI)
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/f-koehler/ansible-role-zfs/main.svg)](https://results.pre-commit.ci/latest/github/f-koehler/ansible-role-zfs/main)
[![Ansible Role](https://img.shields.io/ansible/role/56443)](https://galaxy.ansible.com/f_koehler/zfs)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56443)](https://galaxy.ansible.com/f_koehler/zfs)
[![Ansible Role](https://img.shields.io/ansible/role/d/56443)](https://galaxy.ansible.com/f_koehler/zfs)

Installs `zfs-utils` and kernel modules on Arch Linux.

## Requirements

None.

## Role Variables

Available variables along with their default values:

```yaml
archzfs_kernels: []
```

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
    - { role: fkoehler.zfs }
```

## License

MIT

## Author Information

This role was created in 2021 by [Fabian Köhler](https://fkoehler.xyz)
