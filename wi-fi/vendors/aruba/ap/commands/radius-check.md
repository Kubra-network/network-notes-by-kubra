# Check that AP has access to the RADIUS server 

# AP nin RADIUS server erişimi var mı?

show radius-servers // learn the radius server name

aaa test-server <radiusName> username <testUsername> password <testPassword> auth-type pap

