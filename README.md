NTP
=========

Installs ntp service for time synchronization on Centos 7

Variables
---------

- ntp_zone: e.g. Europe
- ntp_city: e.g. Paris

Example:

/usr/share/zoneinfo/Europe/Paris


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ntp

License
-------

BSD
