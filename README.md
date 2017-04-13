# Ansible Role: Fedora Mirror

Installs the Fedora mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-fedora-mirror.git
      name: nexcess.fedora-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.fedora-mirror

## License

MIT / BSD
