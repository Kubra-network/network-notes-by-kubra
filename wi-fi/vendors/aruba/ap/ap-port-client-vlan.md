# If your Aruba AP is standalone ( not managed by controller or central ) and your client vlan is different from your AP vlan (should be): 

you need to add your clien vlan as a trunk to your AP connected switch port.

# Lightweight Access Points (APs) do not need a trunk port for the client vlan. 

Because:

The controller is responsible for handling VLAN assignments and other network-related tasks. 

APs create a tunnel to the controller.The controller then performs the necessary VLAN tagging and forwards the traffic to the appropriate VLAN on the network.The controller then performs the necessary VLAN tagging and forwards the traffic to the appropriate VLAN on the network.
