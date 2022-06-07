# ansible-apps_ufw

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_ufw-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_ufw)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_ufw.svg)](https://github.com/lotusnoir/ansible-apps_ufw/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_ufw?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_ufw)
[![downloads](https://img.shields.io/ansible/role/d/56848)](https://galaxy.ansible.com/lotusnoir/apps_ufw)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56848)](https://galaxy.ansible.com/lotusnoir/apps_ufw)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Install and configure ufw

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_ufw
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_ufw


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

