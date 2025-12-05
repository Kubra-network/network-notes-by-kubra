# Aruba IAP Assigning a Static IP

To assign a static IP to an IAP:

1.	Connect a terminal, PC, or workstation running a terminal emulation program to the Console port on the IAP.
	
2.	Power on the IAP. An autoboot countdown prompt that allows you to interrupt the normal startup process and access apboot is displayed.
   
3.	Click Enter before the timer expires. The IAP goes into the apboot mode.
   
4.	In the apboot mode, use the following commands to assign a static IP to the IAP.
   
Hit <Enter> to stop autoboot:  0

apboot>

apboot> setenv ipaddr 192.0.2.0

apboot> setenv netmask 255.255.255.0

apboot> setenv gatewayip 192.0.2.2

apboot> save

Saving Environment to Flash...

Un-Protected 1 sectors

.done

Erased 1 sectors

Writing

5.	Use the printenv command to view the configuration.
   
apboot> printenv

6. apboot> boot
