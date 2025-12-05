# External Captive Portal Config for a SSID but Meraki does not send client to the external captive portal. 

Meraki shows internal captive portal screen while client connecting to the SSID.

* Check the external captive portal acessibility from AP and client VLAN
  
* Check for DNS issue:

Try to connect from a computer to the SSID and ping the splash page domain (client resolve the domain?)

Check for DNS server accessibility –check DNS server accessibility from the Meraki AP and get a capture

Try with another VLAN which has all access include DNS

https://n626.network-auth.com/splash/?your_own_excap_url
