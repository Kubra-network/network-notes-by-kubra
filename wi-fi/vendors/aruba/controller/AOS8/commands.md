# Aruba AOS8 (Mobility Controller) Commands

* AP MAC Address based logs
  
show log system all | include <apmac address>   

logging level debug ap-debug <apmac address>    

show log all <apmac address>

* Check connection on the Mobility Conductor to Aruba Controller
  
(ArubaMM-VA_7A_01_1A) *[mynode] #show datapath session  

* Get a file on the controller via tftp

(Aruba7005_BE_7D_68) *#copy tftp: 192.X.X.X ArubaOS_70xx_8.10.0.7_87023 system: partition 0 
