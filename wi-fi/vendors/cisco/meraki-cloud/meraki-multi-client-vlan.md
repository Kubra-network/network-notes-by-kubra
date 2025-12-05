# If you want to add multi VLAN as client vlan for a SSID (which uses external captive portal & RADIUS login) on Meraki 

* filter id attribute can be used :
  
Radius accept has filter-id attribute and it is mapped to the group policy that created on the meraki. Group policy has the vlan information for the client. 

Then add filter-id group policy config to the ssid config:

Navigate to Wireless > Configure > Access control and select the appropriate SSID. 

Under RADIUS attribute specifying group policy name, select the attribute configured earlier. 
