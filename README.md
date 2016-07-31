koji-client
=========

[![Build Status](https://travis-ci.org/kostyrevaa/ansible-koji-client.svg?branch=master)](https://travis-ci.org/kostyrevaa/ansible-koji-client)

Installs Koji (client) for RedHat and optionally configures it.

This is one of the koji- roles which configures the whole koji stack.

Roles are:

 * [koji-ca](https://galaxy.ansible.com/kostyrevaa/koji-ca)
 * [koji-db](https://galaxy.ansible.com/kostyrevaa/koji-db)
 * [koji-client](https://galaxy.ansible.com/kostyrevaa/koji-client)
 * [koji-hub](https://galaxy.ansible.com/kostyrevaa/koji-hub)
 * [koji-web](https://galaxy.ansible.com/kostyrevaa/koji-web)
 * [koji-kojira](https://galaxy.ansible.com/kostyrevaa/koji-kojira)
 * [koji-builder](https://galaxy.ansible.com/kostyrevaa/koji-builder)

For example of all-in-one setup go to [ansible-koji-infra](https://github.com/kostyrevaa/ansible-koji-infra)

Requirements
------------

Installing koji on RedHat-like systems requires EPEL.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
	  vars:
        koji_client_package_only: true
      roles:
          - role: kostyrevaa.koji-client

  

License
-------

MIT / BSD

Author Information
------------------

Send your suggestions and pull requests to https://github.com/kostyrevaa/ansible-koji-client.  
When send PR make sure your changes are backward-compatible.  
You may test your changes to role with https://github.com/kostyrevaa/ansible-koji-infra
