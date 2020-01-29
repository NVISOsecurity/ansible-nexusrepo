# ansible-nexusrepo

An Ansible role for installing Nexus Repository and configuring it as a Chocolatey proxy

## OS Platforms

This role has been tested on the following operating systems:

- Ubuntu 18.04

## Usage

To use this role in your playbook, add the code below:

```
- name: Install Nexus repository
  import_role:
    name: ansible-nexusrepo
```

## Disclaimer

This role is meant for use in the SANS 699 course and is provided as is.

## License

[MIT](LICENSE)