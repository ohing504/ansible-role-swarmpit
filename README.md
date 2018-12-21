# Ansible Role: Swarmpit

[![Build Status](https://travis-ci.org/ohing504/ansible-role-swarmpit.svg?branch=master)](https://travis-ci.org/ohing504/ansible-role-swarmpit)

An Ansible Role the deploy [Swarmpit](https://swarmpit.io/) docker stack on Linux.

## Requirements

* Target has `git` and `docker` running in swarm mode.
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
