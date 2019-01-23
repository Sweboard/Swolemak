Swolemak
========

## Flash instructions (Windows)

* Download QMK-toolbox, found [here](https://github.com/qmk/qmk_toolbox/releases).
* Download the .hex file under the `Code`-tab, then you find it under releases.
* Make sure that the reciever is discovered, if successful a message will appear. 
```
*** Unknown: Mitosis connected  -- FEED:0000:0000
```
* Load the .hex file that you downloaded with the "Local file"-field.
* Reset the reciever by pressing the button closest to the micro USB connector.
* Now a yellow line should be printed.
```
*** Caterina device connected: Arduino Micro bootloader (COM3) -- 0000:0000:0000
```
* Quickly press flash, you only have a couple of seconds!
* A message like this should now appear.
```
*** Attempting to flash, please don't remove device
```
* If successful, you will see this print out.
```
    avrdude.exe: verifying ...
    avrdude.exe: 22904 bytes of flash verified
    
    avrdude.exe done.  Thank you.
```
You are now __DONE__, congratulations!
