Zabbix Agent
=========

Installs and setup Zabbix-Agent 3.0 in Amazon Linux 2017

Installation
------------

erozario.zabbix-agent is an Ansible role distributed globally using Ansible Galaxy. In order to install erozario.zabbix-agent role you can use the following command.

    $ ansible-galaxy install erozario.zabbix-agent


Role Variables
--------------

    - vars:

      zabbix_url: zabbix.example.com
      zabbix_version: 3.0

Example Playbook
----------------

    - hosts: zabbix
      become: yes
      roles:
        - {role: zabbix-agent, zabbix_url: localhost}

License
-------

MIT

Author Information
------------------
https://www.linkedin.com/in/eduardo-rozario/
