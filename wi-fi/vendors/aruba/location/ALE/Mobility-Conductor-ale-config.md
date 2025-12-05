# Aruba Mobility Conductor Topology ALE Configuration for Location Data 

MM: add ALE, add profile (receives AMON)

MD: add profile (sends AMON)

ALE: add MD as a source

* Great source:

https://community.arubanetworks.com/community-home/digestviewer/viewthread?MID=15015#bm359407b3-7dbf-4f4d-b650-31b72998839b


* Controller ---> ALE ---> websocket tunnel (8080-7779-443) 

* FW: Controller > ALE : 8211 (PAPI) ALE > Controller : 4343 (HTTPS)
