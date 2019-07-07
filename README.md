[![Build Status](https://travis-ci.com/calvinbui/ansible-java.svg?branch=master)](https://travis-ci.com/calvinbui/ansible-java)
![GitHub release](https://img.shields.io/github/release/calvinbui/ansible-java.svg)
![Ansible Quality Score](https://img.shields.io/ansible/quality/36550.svg)
![Ansible Role](https://img.shields.io/ansible/role/d/36550.svg)

# Ansible Java

Installs OpenJDK Java. Probably only 8.

##  Requirements

N/A

## Role Variables

`java_version`: Version of Java to install.
`java_headless`: Install headless boolean

## Dependencies

N/A

## Example Playbook

```yaml
- hosts: servers
  become: true
  roles:
    - role: calvinbui.ansible_java
```

## License

GPLv3

## Author Information

http://calvin.me
