# ALE Migration Process

# Backup of ALE Server
 
ssh root@x.y.z.w    

zip -r ALEBackup /var/derby /root/.config/ /opt/ale/license/ /opt/ale/ale-jwebapp/webapp/download/ /etc/ntp.conf   // Zip files from ALE server, generate a ALEBackup.zip file

Store this ALEBackup.zip file on an appropriate location for usage during the restore process. The file returned can be used to restore an ALE server.
  
iptables-save > /tmp/rules.backup

iptables-restore < /tmp/rules.backup

/etc/resolv.conf  // DNS servers

# Restore ALE server
  
To achieve this, you need to have previously captured a backup file from an ALE server (see previous section). To restore this ALE data, here are the steps to follow.

ssh root@x.y.z.w   

Copy previously backup data on new ALE server, scp can be used

monit stop all  // stop all ALE processes

monit summary // make sure all processes are stop

unzip -qq -o backupFile.zip -d /

ifdown ethX   // Turn off Existing ALE server interface (If you don't want to reconfigure all your ALE feeds)

ethX is the interface  ALE is reachable

Configuring the IP Address of the restored ALE Server as  the backup ALE server IP to restore existing feeds to ALE server.

monit start all // Start all ALE processes

monit summary  // make sure all processes are started

systemctl restart ntpd   //Restart ntp server

Log into web UI https://ALEserverIP/ 

ALEServerIP is the original IP used or a new IP used based on your preference.

Validate if the ALE server has restored the ALE configuration.
