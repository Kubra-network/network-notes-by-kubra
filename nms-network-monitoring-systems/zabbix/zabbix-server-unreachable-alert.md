# Server is unreachable alert at Zabbix

count(/example.example.com/icmpping,30m,,"0")>5

The expression is true if host "example.example.com" is unreachable more than 5 times in the last 30 minutes.

zabbix_sender -vv -z 192.168.X.X -s "Cisco 2500 Legacy WLC" -k oxidized.status -o 1
