[![Build Status](https://travis-ci.com/calvinbui/ansible-java.svg?branch=master)](https://travis-ci.com/calvinbui/ansible-java)

# Ansible Java

Installs Oracle Java. Probably only 8.

https://launchpad.net/~webupd8team/+archive/ubuntu/java

##  Requirements

N/A

## Role Variables

`java_version`: Version of Java to install.

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
