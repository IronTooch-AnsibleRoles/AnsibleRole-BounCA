AnsibleRole-BounCA
=========

Installs the BounCA Web Interface tool for self-hosted PKI. BounCA's main repository is https://gitlab.com/bounca/bounca/ 

This has only been tested on Ubuntu 20 server, but should work fine on other Debian-based systems..


![Ansible Role](https://img.shields.io/ansible/role/57813)
[![Ansible Lint](https://github.com/IronTooch/AnsibleRole-BounCA/actions/workflows/main.yml/badge.svg)](https://github.com/IronTooch/AnsibleRole-BounCA/actions/workflows/main.yml)
![Galaxy Downloads](https://img.shields.io/badge/dynamic/json?color=blueviolet&label=Galaxy%20Downloads&query=%24.download_count&url=https%3A%2F%2Fgalaxy.ansible.com%2Fapi%2Fv1%2Froles%2F57813%2F%3Fformat%3Djson) 
![GitHub all releases](https://img.shields.io/github/downloads-pre/irontooch/AnsibleRole-BounCA/total)
![GitHub repo size](https://img.shields.io/github/repo-size/IronTooch/AnsibleRole-BounCA)
![GitHub issues](https://img.shields.io/github/issues-raw/Irontooch/AnsibleRole-BounCA)
![GitHub Open PRs](https://badgen.net/github/open-prs/Irontooch/AnsibleRole-BounCA)
![GitHub last commit](https://img.shields.io/github/last-commit/IronTooch/AnsibleRole-BounCA)
![GitHub Maintained](https://img.shields.io/maintenance/yes/2022)
![GitHub](https://img.shields.io/github/license/IronTooch/AnsibleRole-BounCA)
![Forks](https://img.shields.io/github/forks/Irontooch/AnsibleRole-BounCA.svg)
![Stars](https://img.shields.io/github/stars/Irontooch/AnsibleRole-BounCA.svg)
![Watchers](https://img.shields.io/github/watchers/Irontooch/AnsibleRole-BounCA.svg)
![Follow](https://img.shields.io/github/followers/IronTooch.svg?style=social&label=Follow&maxAge=2592000)

Requirements
------------

None

Role Variables
--------------

server_names: ["server1","server.example.com","11.22.33.44"]


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  - hosts: servers
    roles:
    - role: irontooch.pk_bounca
      vars:
        server_names: ["server1","server.example.com","11.22.33.44"]

To Do
-----

Create Admin User options.

License
-------

GPL-3.0

Author Information
------------------

Author is IronTooch.
