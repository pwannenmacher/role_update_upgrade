# Apt-Upgrade

Installs available Updates on Debian and Ubuntu hosts

## Requirements

none

## Role Variables

none

## Dependencies

Only default modules are used. No dependencies.

## Example Playbook

```yaml
- hosts: all
  become: true

  roles:
    - role: role_update_upgrade
```

## License

MIT

## Author Information

Paul Wannenmacher
