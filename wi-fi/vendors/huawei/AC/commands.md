# Huawei AC commands


System-view 

Dis cu //show running config

Debugging radius all

[AC6508-diagnose]station-trace sta-mac 6e:06:19:e1:a9:6f

undo t m // to stop debug logs on cli

Save // on default mode to save config

debugging web all  // web debug logs

* Enable the function of allowing user name and password information submission to the device in GET mode in the Portal server template.

[HUAWEI] web-auth-server portal_test
[HUAWEI-web-auth-server-portal_test] http get-method enable

[HUAWEI] display aaa online-fail-record
