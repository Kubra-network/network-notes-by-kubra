# Ubuntu monitor mode (wireless network sniffer)

Disable automatic reconnection (this would cause the monitor mode to be exited)

Disconnect the PC from any wifi network

Run these commands

sudo ifconfig wlp3s0 down

sudo iwconfig wlp3s0 mode monitor

sudo ifconfig wlp3s0 up

sudo wireshark

This device acts like a sniffer, does not connect a ssid just listens to the ssid and packets that are around it.

