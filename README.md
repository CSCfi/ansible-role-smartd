ansible-role-smartd
=========

Installs and configures smartd

If it recognizes a DELL disk, then take all the disks found with smartctl --scan except /dev/sda and put them in a clean smartd.conf.

Else: just use the default DEVICESCAN line.

Requirements
------------


Role Variables
--------------

See defaults/main.yml

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-smartd }

License
-------

MIT

Author Information
------------------

Inspiration taken from https://github.com/libreit/ansible-smartd
