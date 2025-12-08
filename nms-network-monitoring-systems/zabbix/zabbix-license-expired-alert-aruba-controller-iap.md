# Aruba Controller and IAPs alerting with Zabbix

#show snmp trap-list // wlsxLicenseExpiry & wlsxLicenseServerExpiry

Aruba Controller: If you type "show ap database", it will tell you why your APs are disabled

* IAP :

(Instant Access Point)(config)# snmp-server host <IP-address> {version 1 | version 2 | version 3} <name> udp-port <port> inform

(Instant Access Point)(config)# end

(Instant Access Point)# commit apply
