# ansible-system_nfs_mount

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_nfs_mount-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_nfs_mount)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_nfs_mount.svg)](https://github.com/lotusnoir/ansible-system_nfs_mount/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_nfs_mount?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_nfs_mount)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/system_nfs_mount)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/system_nfs_mount)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Install and configure nfs mount points
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_nfs_mount
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_nfs_mount


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
