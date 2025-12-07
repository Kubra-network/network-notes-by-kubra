# ALE CLI Commands that will help troubleshooting

* free -g       // check the system memory usage

* cat centos-release      // heck the CentOS version of the ALE appliance

* df -h      // sisplays disk usage of all partitions in human-readable format.

* tcpdump -i eth1 -w /tmp/ale.pcap    // Starts a packet capture ( between Mobility Controller / MM / APs and ALE ) on interface eth1 and writes it to /tmp/ale.pcap . 

* cd /tmp    // go to tmp directory 

* ls -lFh    // lists files in the directory in human-readable format

* monit summary  // to check if ALE services (feed processors, database, API services) are up
