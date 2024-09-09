<span style="color:red">**[STATUS: IN PROGRESS]**</span>

This guide will be improving over time and hopefully some day will cover everything the app has to offer. Before you start reading there are two very important things you need to know. In order to use it you must have:

* [VESC®](https://vesc-project.com)-based controller
* [Voyage Systems](http://shop.voyagesystems.eu/) telemetry device

If your PEV has another ESC, the app will not work for you. For example Boosted, Evolve, Mellow, Meepo, WowGo, Backfire have another type of controller and are not compatible.


### Contents

[⚙️ Firmware](#heading--voyagefwupdate)  
[📈 Realtime](#heading--realtime)  
[👤 Account](#heading--account)  
[⚙️ Settings](#heading--settings)  
[🛠 Troubleshooting](#heading--troubleshooting)  


<h3 id='heading--realtime'>📈 Realtime</h3>

Shows values such as voltage, current, temperature from your ESC at any given time. Each value is displayed in it's own cell. Following cells are available:

* Voltage
* Cell voltage (per cell)
* Battery charge (%)
* Battery current
* Motor current
* ESC temperature
* Motor temperature
* Distance
* Duty cycle (%)
* Amp hours (+regen)
* Watt hours (+regen)
* Speed, GPS speed
* Consumption (Wh/km)

It is possible to arrange/resize/recolour cells:

* ...
* ...
* ...
* Touch colour palette to change colour
* ...

There is an indicator in the bottom which shows currently selected telemtery device and connection status. It blinks every time a new packet from it is received.

<img  width="220">

<h3 id='heading--account'>👤 Account</h3>

You can sign in to your account at [https://cloud.voyagesystems.eu](https://cloud.voyagesystems.eu) and view stats and all records for all your Voyage Systems devices.

<img width="320">

<h3 id='heading--settings'>⚙️ Settings</h3>

Make sure motor settings are configured correctly

<img width="400">

And battery settings

<img width="400">

[LLT BMS](https://www.lithiumbatterypcb.com/product-category/smart-bms/) comes with it's own BLE module instead of CAN bus. It is possible to connect to LLT BMS using following steps:

* Navigate to Settings → Battery

<img width="400">

* Click on "Pair with BMS"

<img width="400">

* Select LLT BMS
* Go back to Realtime tab and click on Battery bar. You should see cell information

<img width="400">


<h3 id='heading--troubleshooting'>🛠 Troubleshooting</h3>

A good advice is to search for information on [esk8.news forum](https://forum.esk8.news). Maybe you will find the solution.

If you didn't find anything relevant, could be that you found a bug! The bugs are always there🐛 and once in a while a new one pops out. If you want to report it, please collect the log file from the app. Open Settings and click on "Show Logs" button. Send log file toghether with the bug description to info@voyagesystems.eu, screenshots or video.

This guide is written in [Markdown](https://en.wikipedia.org/wiki/Markdown) and is available at

[GitHub](https://github.com/voyagesystems/voyage-connect-guide/) (contributions welcome)  
