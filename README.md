
## software and drivers for the Canduino boards compatible with arduino uno,


These files are available on GitHub:

https://github.com/lembed/Lembed-Canduino-Firmware



## Add-on 
copy the "add-on" to "hardware" subfolder of Arduino location, and rename "add-on" to
"canduino" for best recognation.



## Drivers
The Canduino use ft232rl as usb-uart bridge interface, the drivers of all platform can download
from the ftdi website.




## udev rules
Copy the "99-usb-serial-canduino.rules" inside "udev-rules" to "/etc/udev/rules.d/" of your os
, it will tell ModemManager to not try to access the virtual serial ports of the canduino.
type "sudo restart udev" in teminal of your linux, to make it work.



## License
Please review the LICENSE.md file for license information. 

[![](https://ga-beacon.appspot.com/UA-67438080-1/Lembed-Canduino-Firmware/readme?pixel)](https://github.com/lembed/Canduino)
