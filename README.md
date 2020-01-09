# zabbix

This template is based on "Template Net Brocade_Foundry Stackable SNMPv2", requires the following templates to be linked (included in the Download):

Template Module Brocade_Foundry Performance SNMPv3

Template Module Generic SNMPv3

Template Module Interfaces SNMPv3

 

SNMPv3 authPriv level is implemented in these four templates, requires the following macros for SNMPv3 authPriv credentials:

{$SNMP_V3_SECURITYNAME}

{$SNMP_V3_AUTHKEY}

{$SNMP_V3_PRIVPASSWORD}

 

- Updated 9 JAN 2020, added interface utilization, ignore down interfaces, use ifHCInOctets, ifHCOutOctets, ifHighSpeed for more accurate readings, added interface macros and filters, bug fixes.

- Updated 19 DEC 2019, bug fixes, very important to use v1.2

- Updated 9 DEC 2019, added temperature graphs, chassis temperature graph.
