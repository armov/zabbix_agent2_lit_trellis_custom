Role Name
=========
Custom role to install Zabbix Agent2 with autoregistration option


Requirements
------------
Intended for Ubuntu: 20.x and 22.x


Role Variables
--------------
These variables must be defined in trellis vault:
zabbix_server: "zabbix.server"
zabbix_psk_identity: "YOURIDENTITY"
zabbix_psk_key: "hex format"
hostmetadatafilter: "your-filter"

License
-------
BSD

Author Information
------------------
by: armov
