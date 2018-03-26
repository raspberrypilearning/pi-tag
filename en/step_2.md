## What you will need

### Hardware

You will need one set of hardware per player, for example, if you have two tag players, you will need to double the kit quantities on this list.

+ 1× Raspberry Pi Zero **or** Zero W **or** Zero WH
+ 1× male header **or** male [hammer header](https://shop.pimoroni.com/products/gpio-hammer-header){:target="_blank"} (if you're not using the Zero WH)
+ 1× USB battery pack

We recommend using the [Monk Makes Clever Card Kit](https://www.monkmakes.com/cck/){:target="_blank"}, which contains all of the following components:

+ 1× RFID tag reader
+ 1× RFID tag or card
+ 7× female-female jumper leads
+ 1× Pre-wired RGB LED

**If you are not using the kit**, you will need:

+ 1× RFID tag reader
+ 1× RFID tag or card
+ 11× female-female jumper leads
+ 1× RGB LED
+ 3× 100 Ohm resistors

### Software

+ Python 3 (comes as standard with Raspbian)
+ SPI-Py
+ MFRC522 and SimpleMFRC522

--- collapse ---
---
title: Easy software installation
---

+ Open a terminal window.

+ Type the following commands, pressing <kbd>Enter</kbd> on the keyboard in between each one:

```
cd /home/pi
wget http://monkmakes.com/downloads/mmcck.sh
chmod +x mmcck.sh
./mmcck.sh
sudo reboot
```

Your Raspberry Pi will reboot after the final command.

The Clever Card Kit software is used under the [MIT Licence](https://github.com/raspberrypilearning/pi-tag) and is copyright (c) 2016 Simon Monk.

--- /collapse ---

### Additional resources

+ Old T-shirt or sports bib
+ Needle and thread
+ Glove
+ Soldering iron
+ Hammer (optional, depending on your chosen header)
