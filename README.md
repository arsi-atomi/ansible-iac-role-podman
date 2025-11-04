ANSIBLE-ROLE-PODMAN
===================
**COPYRIGHT** 2025 ^(ida|arsi)$ collective  
**LICENSE** MIT License [LICENSE](LICENSE)  
**AUTHORS**
- Arsi Atomi <arsi@atomi.sh>  

Overview
========

This Ansible role is designed to simplify and enhance the flexibility of Podman management.

This role uses only ansible.builtin.* ansible modules.

Supported Podman versions:


These operations are supported:

Operation                       | State               |
--------------------------------|---------------------|
Installing Podman               | present             |
Uninstalling Podman             | absent              |
Creating container              | container_present   |
Removing container              | container_absent    |
Starting container              | container_started   |
Stopping container              | container_stopped   |

Requirements
------------

- Operating system (one mandatory)
  - Rocky Linux 10

- Other components
  - Ansible 2.16 or higher

