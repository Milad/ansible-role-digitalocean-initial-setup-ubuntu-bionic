Role Name
=========

This role performs the initial setup instructions on new Ububntu servers as recommended by digialocean.com. It is a collection of commands from these pages:

- [Initial Server Setup with Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-18-04)
- [How to Set Up SSH Keys on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-on-ubuntu-1804)
- [How to Use Ansible to Automate Initial Server Setup on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-use-ansible-to-automate-initial-server-setup-on-ubuntu-18-04)

Requirements
------------

This role assumes that we are connecting to the remote machine with a root user.

Role Variables
--------------

Check the file [defaults/main.yml](./defaults/main.yml) for details.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

Milad Kawas. @miladkawas
