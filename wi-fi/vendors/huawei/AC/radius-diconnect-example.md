# Huawei AC RADIUS Disconnect Example

When you want to disconnect a client, you need to send the required attributes : User-Name, Acct-Session-Id, Framed-IP-Address, Calling-Station-Id

echo "User-Name=XXX", "Acct-Session-Id=AC65080000000000000144db10020XXX", "Framed-IP-Address=X.X.X.X", "Calling-Station-Id=XXXX-XXXX-XXXX" | radclient X.X.X.X:3799 disconnect <radiusKey> 
