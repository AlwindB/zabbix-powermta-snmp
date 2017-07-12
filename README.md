# zabbix-powermta-snmp
Zabbix SNMP template based on PowerMTA SNMP MIBs

# Requirements
- PowerMTA MIBs installed within Zabbix

## Zabbix Server

Import the zabbix-powermta-snmp_template.xml file into Zabbix and assign it to the hosts you want to collect stats on.

## Configuration
Zabbix template requests information on port 162 to avoid issues with regular SNMP requests
