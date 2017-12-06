Generic MOTD
=========

A really small role to set the MOTD on various platforms

Requirements
------------

None

Role Variables
--------------

```

generic_motd_file_src: "motd.j2"
generic_motd_file_dest: "/etc/motd"
generic_motd_owner: root
generic_motd_group: root

```
Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: generic-motd, generic_motd_group: wheel }

License
-------

BSD

Author Information
------------------

Sebastien Perreault
