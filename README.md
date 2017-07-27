# Ansible Role - Memcached for Docker

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-docker-memcached.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-docker-memcached)

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
docker_memcached_version: "1.5"
docker_memcached_container_name: "memcached"
docker_memcached_container_port: "11211"
docker_memcached_pull: "yes"
docker_memcached_state: "started"
docker_memcached_restart_policy: "always"
```

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