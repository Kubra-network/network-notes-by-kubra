# RADIUS Server connection check from Aruba Central 

At Aruba Central topology, the VC AP sends traffic to the Radius Server for all group. 

To verify the accessibility, the control can be performed either through the AP's CLI or by navigating to Central > Analyze > Tools section and executing the following commands:

show radius-servers // To obtain the Radius server IP addresses and names

aaa test-server <radiusName> username test password test auth-type pap

The output should be "Radius server <radiusName> test successfully".
