# Ansible Role for Installing Basic Compiling Tools (GCC)

## Dependency

May become dependent of [repo-epel](https://github.com/dragoscirjan/ansible-role-repo-epel) in the future.

## Usage

```yaml
---
  - hosts: all
    sudo: true
    roles:
      - repo-base-devel
```
