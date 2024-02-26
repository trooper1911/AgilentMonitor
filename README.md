# AgilentMonitor
monitor Agilent LC1260/1290/1100 with very cheap esp32 devboard LOLIN_s2_mini

1. burnning the firmware
2. connect the devboard to Agilent LC with TypeC-MiniUSB cable. 5V additional supply to VBUS port is better
3. scan the wifi, you will find a AP AgilentMonitor_XXXX
4. connect to the AP,  and visit http://192.168.4.1
5. the data will be flush every 1s
6. if you want to get the bare data, http client get http://192.168.4.1/query
7. enjoy
