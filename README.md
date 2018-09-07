# ansible-install

An ansible playbook to install basic tools on a development machine.

It installs everything listed in the roles **base**, **golang** and **vscode**. Comment roles/tasks to disable them.

the role **base** installs:
- docker-ce
- docker-compose
- git
- curl
- openvpn
- google chrome
 

Tested on ubuntu 18.04 (but works also on macOS).

A recent version of ansible is required.

Launch with `ansible-playbook install.yml` or `ansible-playbook -k -K install.yml`

