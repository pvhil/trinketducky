# trinket-ducky
Hello! This is my Fork from [pico-ducky!](https://github.com/dbisu/pico-ducky) This Repo is specially made and edited for the Trinket M0, because I think the Trinket is better than a Pico. (Veeery much smaller and cooler :^). I have an example down below).
(I have not changed that much in the Code I just made it compatible to the Trinket. BUT I will add some cool features in the future)

Create a USB Rubber Ducky like device using a Trinket M0

Download circuitpython for the Trinket: (I use 7.0 beta)
https://circuitpython.org/board/trinket_m0/

Plug the Trinket into a USB port with an micro-USB cable.
The Trinket will show up as a removable media device.
Copy the UF2 file to the root of the media device.

The Trinket will reboot after installing the firmware image.

Download additional libraries (for your version, 6x or 7x):
https://github.com/adafruit/Adafruit_CircuitPython_Bundle

https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/tag/20210130

from zip file, unpack adafruit_hid folder.
copy adafruit_hid to the lib folder.

Circuitpy HID
https://learn.adafruit.com/circuitpython-essentials/circuitpython-hid-keyboard-and-mouse


# Ducky Script Python
Copy duckyinpython.py to the root of the media device as code.py

$ cp duckyinpython.py /<path to media device>/code.py

Copy your Ducky Scipt file as payload.dd

$ cp <duckyscriptfile> /path to media device>/payload.dd

# You want to change the script?   
Simply press the button on the Trinket when connecting to a PC while it is flashing YELLOW. It will run in Secure Mode and you can change anything you want.
  
# Cool Example
My First Version (v1)   
![](https://raw.githubusercontent.com/pvhil/trinket-ducky/main/pics/image1.jpg)  
    
     
Final Version (v2) in a small USB :D   
![](https://raw.githubusercontent.com/pvhil/trinket-ducky/main/pics/image0.jpg)   
    
