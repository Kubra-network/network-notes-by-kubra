# Meraki Redirection process — explained

When a client connects to the Wi-Fi network and obtains an IP address, the client will send an HTTP GET packet to a predefined domain. Apple devices send the HTTP GET to captive.apple.com, Android devices use connectivitycheck.gstatic.com while Windows devices use msftconnectest.com. Browsers themselves also perform an additional HTTP get request to check for internet connectivity.

Meraki- whitelist - connect static devices without captive portal:

Clients→ Add client →add client with the mac address as whitelisted
