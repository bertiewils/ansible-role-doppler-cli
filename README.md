# Ansible role: Doppler CLI

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/bertiewils/ansible-role-doppler-cli/test.yml?label=tests)
![latest SemVer release](https://img.shields.io/github/v/release/bertiewils/ansible-role-doppler-cli?label=latest)


Install the [Doppler](https://www.doppler.com) CLI.

## Supported Distros

- Alpine
- Debian
- RedHat

...and derivatives.

## Requirements

None.

## Installation

```
ansible-galaxy install bertiewils.doppler_cli
```

## Role variables

None.

## Example playbook

```yml
- hosts: all
  roles:
    - bertiewils.doppler_cli
```
