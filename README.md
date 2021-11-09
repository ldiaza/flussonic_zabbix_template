# flussonic_zbx_template
Template for monitor streams info and status by Zabbix, tested with Zabbix Server 5.0
Developed by Luis Díaz - wse.ldiaz@gmail.com 

First configure SNMP port in Flussonic Web Interface, add host monitored by snmp in Zabbix Server and include this template in the host monitoring.

General Items:
- Server Uptime
- Total Connected Clients
- Total Stream Number

Stream Items:
- Streams Bitrate (Mbps)
- Streams Client Watching Count
- Streams Retry Count
- Streams Status
- Streams Uptime

Triggers for streams status checking, restart checking and more!
