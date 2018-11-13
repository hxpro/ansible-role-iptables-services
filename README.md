hxpro.iptables-services
=======================

I prefer iptables-services instead of firewalld. This role ensure that firewalld is disabled and iptables-services is enabled. This role is in development state and tested on CentOS7 vagrant box.

Requirements
------------

CentOS 7

Role Variables
--------------

#TODO Paste here defaults/main.yml

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: hxpro.iptables-services

License
-------

WTFPL

Author Information
------------------

Matěj Koudelka <matej@hxpro.cz>
