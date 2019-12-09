# fail2ban

An Ansible role to install and configure fail2ban.

## Requirements

A server which runs services that should be protected by fail2ban.

## Role Variables

Many. See defaults/main.yml.

## Dependencies

None.

## Install this role as submodule of an existing GIT repository

`git submodule add https://git.sekoya.org/mb/fail2ban.git roles/fail2ban`

## Example Playbook

    - hosts: servers
      roles:
        - fail2ban


    - hosts: servers
      roles:
        - { role: fail2ban, x: 42 }

## License

GPLv3

## Author Information

<a href="http://www.sekoya.org" target="new">http://www.sekoya.org</a>
