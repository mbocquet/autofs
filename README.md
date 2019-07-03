# autofs

Ansible role to install and configure autofs.

## Requirements

None.

## Role Variables

Many. See defaults/main.yml

## Dependencies

None.

## Install this roles as submodule of an existing GIT repository

`git submodule add https://github.com/mbocquet/autofs.git roles/autofs`

## Example Playbook

    - hosts: servers
      roles:
         - autofs


    - hosts: servers
      roles:
         - { role: autofs, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
