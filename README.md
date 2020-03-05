This is a metapackage for installing the required tooling to
do development on the esp8266.

It's probably not useful to anybody but me, and it's purpose
is to track whatever I can get to work for other projects.

It is inspired by 
https://github.com/pfalcon/esp-open-sdk
Which unfortunately hasn't been updated in over a year, and which
has a stated goal of "The idea behind esp-open-sdk was to provide 
conservative set of tools known to work (across years).", and is
consequently not taking many updates...


This repository is being tested against MacOSX Catalina and
linux mint.

I use macports on Catalina (and not homebrew)

It pains me deeply, but for now, I'm using blobs from espressif until
I can figure out how to make updated ng-crosstools from source like
is done with the older stuff at https://github.com/pfalcon/esp-open-sdk

https://github.com/espressif/ESP8266_RTOS_SDK

This means the crosstools-ng submodule is not currently being built or used.

This whole endeavor is largely based on the unfortunate aging of
https://github.com/SuperHouse/esp-open-rtos

in particular...
https://github.com/SuperHouse/esp-open-rtos/issues/699

which has prompted me to refresh and use the more recent espressif
ESP8266_RTOS_SDK rather than esp-open-rtos...


