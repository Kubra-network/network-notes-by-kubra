# Check that AP has access to the RADIUS server 

show radius-servers // learn the radius server name

aaa test-server <radiusName> username <testUsername> password <testPassword> auth-type pap

