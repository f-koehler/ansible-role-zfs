# Ansible Role: archzfs

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
    - { role: fkoehler.archzfs, x }
```

## License

MIT

## Author Information

This role was created in 2021 by [Fabian Köhler](https://fkoehler.xyz)
