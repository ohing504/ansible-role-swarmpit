# Ansible Role: Swarmpit

An Ansible Role the installs [Swarmpit](https://swarmpit.io/) on Linux.

## Requirements

* Swarmpit supporting Docker 1.13 and newer.

## Role Variables

* [defaults/main.yml](https://github.com/ohing504/ansible-role-swarmpit/blob/master/defaults/main.yml)

## Dependencies

* `docker` should be installed and working (you can use the [geerlingguy.docker](https://galaxy.ansible.com/geerlingguy/docker) role to install).

## Example Playbook

```yaml
- hosts: servers
  roles:
    - { role: ohing504.swarmpit, become: yes }
```

## License

MIT / BSD

## Author Information

This role was created in 2018 by [Youngsup Oh](https://github.com/ohing504).
