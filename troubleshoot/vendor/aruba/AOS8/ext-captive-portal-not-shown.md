# Aruba AOS8 SSID External Captive Portal not shown issue

There was a BUG that while WLAN editing, Controller adds an internal radius server as the first radius server. Check your version!

* Add host (captive) as a url to wlan, it will make it domain automatically. If this doesn't work, create the radius server on the wlan creation.

* If the problem occurred while WLAN creation, delete that and create again. Editing will not solve the auto creation problems.
