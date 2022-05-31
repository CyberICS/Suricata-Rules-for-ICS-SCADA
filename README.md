# Suricata rule set for the industrial environment

Suricata rule created to detect scan tools targeting PLC interfaces.

The detected tools:
- nmap with the modbus script https://github.com/nmap/nmap/blob/master/scripts/modbus-discover.nse)
- msfconsole (modbus_banner_grabbing and modbusdetect)
- Zgrab2 https://github.com/zmap/zgrab2
- nmap with bacnet script https://github.com/nmap/nmap/blob/master/scripts/bacnet-info.nse

Suricata is a network IDS, IPS and NSM engine developed by the OISF and the Suricata community :
https://github.com/OISF/suricata
