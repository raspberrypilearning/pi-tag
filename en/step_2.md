## What you will need

### Hardware

You will need one set of hardware per player, so for example if you have two tag players you will need to double the kit quantities on this list.

We recommend using the [Monk Makes clever card kit](https://www.monkmakes.com/cck/){:target="_blank"} which contains all of the following components:

+ RFID tag reader
+ RFID tag or card
+ 7 female-female jumper leads
+ Pre-wired RGB LED

If you are not using the kit you will need a RGB LED, 3x100 Ohm resistors and 4 additional female-female jumper leads to replace the pre-wired LED.

Plus:

+ Raspberry Pi Zero or Zero-W
+ Male header OR male [hammer header](https://shop.pimoroni.com/products/gpio-hammer-header){:target="_blank"}
+ USB battery pack

### Software

+ Python 3 (comes as standard with Raspbian)
+ SPI-Py
+ MFRC522 and SimpleMFRC522

--- collapse ---
---
title: Easy software installation
---

+ Open a terminal

+ Type the following commands, pressing <kbd>Enter</kbd> on the keyboard in between each one:

```
cd /home/pi
wget http://monkmakes.com/downloads/mmcck.sh
chmod +x mmcck.sh
./mmcck.sh
sudo reboot
```

Your Raspberry Pi will reboot after the final command.

The clever card kit software is used under the [MIT Licence](https://github.com/raspberrypilearning/pi-tag) and is Copyright (c) 2016 Simon Monk.

--- /collapse ---

### Additional Resources

+ Old t-shirt or sports bib
+ Needle and thread
+ Glove
+ Soldering iron
+ Hammer (optional, depending on your chosen header)
