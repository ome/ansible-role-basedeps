Base Dependencies
=================

[![Actions Status](https://github.com/ome/ansible-role-basedeps/workflows/Molecule/badge.svg)](https://github.com/ome/ansible-role-basedeps/actions)
[![Ansible Role](https://img.shields.io/ansible/role/41039.svg)](https://galaxy.ansible.com/ome/basedeps/)

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
