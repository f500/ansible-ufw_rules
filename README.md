Ufw
========

Install UWF (Uncomplicated Firewall)

Requirements
------------

Debian Wheezy with the package python-pycurl and python-software-properties installed.
Requires the ufw firewall to be installed on the guest.

Role Variables
--------------

ufw_rules_allow_ports: []


Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: f500.ufw_rules, ufw_rules_allow_ports[22, 80, 443] }

License
-------

LGPL.

Author Information
------------------

Jasper N. Brouwer, jasper@nerdsweide.nl

Ramon de la Fuente, ramon@delafuente.nl
