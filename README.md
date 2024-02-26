# AgilentMonitor
monitor Agilent LC1260/1290/1100 with very cheap esp32 devboard LOLIN_s2_mini

1. burnning the firmware
2. scan the wifi, you will find a AP AgilentMonitor_XXXX
3. connect to the AP,  and visit http://192.168.4.1
4. the data will be flush every 1s
5. if you want to get the bare data, http client get http://192.168.4.1/query
6. enjoy
