# Zabbix 7.0 Template for HARES NVR 
Zabbix Template for HARES NVR-A64RH-16D (Enterprise OID 1.3.6.1.4.1.25506). 
The NVR exposes a minimal SNMP agent: all data is text strings under 1.3.6.1.4.1.25506.20, 
parsed here with REGEX / JavaScript preprocessing (dependent items).

CPU Utilization
Memory Utilization
Uptime
Disk Status
Raid Status
Disk Group Status
Disk Usage
Interface Traffic
Scan all cameras
All Camera Status ( Firmware, IP Address, Model, Online/Offline, Status )
All Channel Status ( Encode type, bit rate )
Service Availability ( Ping, SNMP, HTTP, HTTPS, Telnet, RTSP, ONVIF )

39 Items and 18 Triggers: ( CPU, Memory, Camera, ICMP, ... )

Best Regards
Mahdi Alipour
