# If IAP status is unsynchronized at Aruba central group 

Solution : Select a stable firmware. Also all APs need to be in the same vlan, on the cluster mode with the same firmware and same country code. 

check the group site on the central

try to make IAP local and attach the central again 

try to upgrade the IAP




# IAP - Central connection check commands
  
show activate

show activate status

show ap debug cloud-config-received

show ap debug cloud-state

