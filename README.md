Public Stations
=========

This role configures a base ubuntu server image to host an LXC container used for public computing.

Example Playbook
----------------

    - hosts: public_stations
      roles:
         - { role: aadl.public_station }

License
-------

GNU General Public License v3.0
