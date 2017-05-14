# Discovery of onion omega 2

[Omega 2](https://onion.io/omega2/) is a small linux server built for IoT. It has the size of an arduino but can run node.js.
After participating to the [Kickstarter](https://www.kickstarter.com/projects/onion/omega2-5-iot-computer-with-wi-fi-powered-by-linux), I received the Omega 2 and a arduino dock. So it is time to benchmark it!


# Getting started

* power on and wait until it boots
* find the 4 last letters of the address MAC (called **ABCD** for the tutorial)
* connect to the wifi **Omega-ABCD** (the default password is 12345678)
<!-- * go to http://omega-ABCD.local/ -->
* `ssh root@omega-ABCD.local` (default password is `onioneer`)
* `wifisetup`: setup wifi
* `oupgrade`: uprade

# Arduino

https://wiki.onion.io/Tutorials/Arduino-Dock/Using-the-Arduino-Dock


This repository regroups several projects using Omega 2:









# Links

* [Official website](https://onion.io/)
* [Kickstarter](https://www.kickstarter.com/projects/onion/omega2-5-iot-computer-with-wi-fi-powered-by-linux)
* [Node.js on Omega 2](https://wiki.onion.io/Tutorials/Installing-NodeJS)
