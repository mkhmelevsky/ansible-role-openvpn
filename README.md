# Ansible Role: OpenVPN
=========

## Summary

  This role installs and configures OpenVPN server on RedHat / CentOS hosts

## Role tasks

  - Task 1
  - Task 2

## Requirements
------------

  - Minimal Version of the Ansible for installation: 2.4
  - Supported OS:
      - RHEL
          - 6
          - 7
      - CentOS
          - 6
          - 7

## Role Variables
--------------

  Available variables are listed below along with their default values.

  ```yaml
    - openvpn_port: 1194
  ```

## Dependencies
------------

  This role has no external dependencies

## Example Playbook
----------------

```yaml
  ---

  - name: Apply role ansible-role-openvpn to every host in group 'all'
    hosts: all
    become: True
    roles:
      - role: ansible-role-openvpn

```


## License
-------

Licensed under the MIT License. See the LICENSE file for details.

## Author Information
------------------

Parts are derived from https://github.com/Stouts/Stouts.openvpn

Author:
  - Max Khmelevsky <max.khmelevsky@yandex.ru>

