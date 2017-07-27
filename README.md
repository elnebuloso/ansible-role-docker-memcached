# Ansible Role - Memcached for Docker

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-docker-memcached.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-docker-memcached)

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Role Variables

- [`defaults/main.yml`](https://github.com/elnebuloso/ansible-role-docker-memcached/blob/master/defaults/main.yml)

## Example Playbook

```
- hosts: localhost
  roles:
    - role: elnebuloso.docker-memcached
```

## Dependencies

- `docker` should be installed and working (you can use the `elnebuloso.docker` role to install).

##  License

MIT

##  Author Information

This role was created in 2016 by [elnebuloso](https://github.com/elnebuloso/)