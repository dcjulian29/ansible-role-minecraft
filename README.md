# Ansible Role: minecraft

[![Lint](https://github.com/dcjulian29/ansible-role-minecraft/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-minecraft/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-minecraft.svg)](https://github.com/dcjulian29/ansible-role-minecraft/issues)

This an Ansible role to install my take on a Minecraft server. Various flavors
include: Vanilla, Paper, Spigot, and Bedrock.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.minecraft
  src: https://github.com/dcjulian29/ansible-role-minecraft.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
