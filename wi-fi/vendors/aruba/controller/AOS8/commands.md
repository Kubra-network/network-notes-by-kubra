# Aruba AOS8 (Mobility Controller) Commands

* AP MAC Address based logs
  
show log system all | include <apmac address>   

logging level debug ap-debug <apmac address>    

show log all <apmac address>

* Check connection on the Mobility Conductor to Aruba Controller
  
(ArubaMM-VA_7A_01_1A) *[mynode] #show datapath session  
