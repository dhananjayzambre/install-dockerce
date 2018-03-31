Role Name:
=========

Installing Docker CE using Ansible Playbook

Requirements:
------------

- Expects CentOS/RHEL 7.x based system
- Minimum Ansible Version : 1.2

This playbook installs Docker CE on RHEL/CentOS 7.x based systems. To use this, first edit the "inventory" file to contain the hostname of the system where docker is to be installed.

Running the Playbook:
----------------

To run the playbook, use this:

ansible-playbook install-dockerce.yml -i inventory

License
-------

BSD

Author Information
------------------

Diptajeet Khan
