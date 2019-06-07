Base Dependencies
=================

[![Build Status](https://travis-ci.org/ome/ansible-role-basedeps.svg)](https://travis-ci.org/ome/ansible-role-basedeps)
[![Ansible Role](https://img.shields.io/ansible/role/41038.svg)](https://galaxy.ansible.com/ome/basedeps/)

Base dependencies for most servers.

These dependencies should be suitable for installation on a minimal production server.


Role Variables
--------------

- `basedeps_install_lsb`: Install Linux Standard Base (LSB) packages, default `true`.


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ome.basedeps }


Author Information
------------------

ome-devel@lists.openmicroscopy.org.uk


License
-------

BSD
