# Ansible Role: network

[![Build Status](https://img.shields.io/travis/arillso/ansible.network.svg?branch=master&style=popout-square)](https://travis-ci.org/arillso/ansible.network) [![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=popout-square)](https://sbaerlo.ch/licence) [![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-network-blue.svg?style=popout-square)](https://galaxy.ansible.com/arillso/network) [![Ansible Role](https://img.shields.io/ansible/role/d/id.svg?style=popout-square)](https://galaxy.ansible.com/arillso/network)

## Description

This role ensures that the initial network configuration is properly setup using NetworkManager for Linux and NetAdapter for Windows. Additionally it can apply network-related Kernel parameters via sysctl in Linux.

## Installation

```bash
ansible-galaxy install arillso.network
```

## Requirements

## Role Variables

## Dependencies

## Example Playbook

```yml
- hosts: all
  roles:
    - arillso.network
```

## Changelog

## Author

- [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2019, Arillso
