# Exact Audio Copy Ansible role

![CI](https://github.com/baztian/ansible-eac/workflows/CI/badge.svg)

Role to setup Exact Audio Copy via wine inside docker container.

## Example Playbook

    - hosts: servers
      become: yes
      roles:
         - role: baztian.eac

## License

MIT
