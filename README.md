# Ansible Role for Darktable

<img src="/alvistack.svg" width="75" alt="AlviStack">

[![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline/alvistack/ansible-role-darktable/master)](https://gitlab.com/alvistack/ansible-role-darktable/-/pipelines)
[![GitHub tag](https://img.shields.io/github/tag/alvistack/ansible-role-darktable.svg)](https://github.com/alvistack/ansible-role-darktable/tags)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-darktable.svg)](https://github.com/alvistack/ansible-role-darktable/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.darktable-blue.svg)](https://galaxy.ansible.com/alvistack/darktable)

Ansible Role for Darktable Installation.

## Requirements

This role require Ansible community package 4.10 or higher.

This role was designed for:

  - Ubuntu 18.04, 20.04, 21.10, 22.04
  - CentOS 7, 8 Stream, 9 Stream
  - openSUSE Leap 15.3, Leap 15.4, Tumbleweed
  - Debian 10, 11, Testing
  - Fedora 34, 35, 36, Rawhide
  - RHEL 7, 8, 9

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

[ansible-galaxy-requirements.yml](ansible-galaxy-requirements.yml)

## Example Playbook

[molecule/default/converge.yml](molecule/default/converge.yml)

This role could simply deploy to `localhost` as below:

    molecule converge -s default

## License

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

## Author Information

  - Wong Hoi Sing Edison
      - <https://twitter.com/hswong3i>
      - <https://github.com/hswong3i>
