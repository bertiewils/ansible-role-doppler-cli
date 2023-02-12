# Ansible role: Doppler CLI

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
