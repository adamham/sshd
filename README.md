ssh
=========

A role to install and configure sshd. Useful for locking down sshd.

For CentOS, Redhat, Debian or Ubuntu

Tested using Ansible 2.1.2 on:

CentOS 7
Debian Jessie
Ubuntu Trusty

Requirements
------------

Ansible 2+

Role Variables
--------------

See defaults/main.yml
[ OpenSSH SSH daemon configuration file](https://linux.die.net/man/5/sshd_config)


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: true
      roles:
         - sshd

License
-------

MIT
