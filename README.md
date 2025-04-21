Role Name
=========
Custom role to install Zabbix Agent2 with autoregistration option


Requirements
------------
Intended for Ubuntu: 20.04, 22.04 and 24.04


Role Variables
--------------
These variables must be defined in trellis vault:
zabbix_server: "zabbix.server"
zabbix_psk_identity: "YOURIDENTITY"
zabbix_psk_key: "hex format"
hostmetadatafilter: "your-filter"

Defaults:
defaults/main.yml: zabbix_target_version: "Wanted version. e.g.: 7.2"

License
-------
BSD

Author Information
------------------
by: armov
