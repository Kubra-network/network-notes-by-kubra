# Zabbix Alerting System

In order to get alerts, few things need to be done.

So,

1. check you have some active Media type configured (Administration - Media types). 
   
2. configure Administration - Users (select user) - Media for the same communication type.

3. Based on Items you collecting from devices, configure Trigger (problem definition). As example: generate warning, if SNMP check have no data in last 5 minutes.
  
4. configure an action to generate message if Problem detected (Configuration - Actions)

Do not worry, everything, except Triggers need to be configured just once.
To simplify future setup, it is recommended to configured Triggers on Templates (not directly to hosts).

* Host: monitor endpoint
* item: collect info
* trigger: how to use info
* update interval at item : how often you collect the data
