## What you will need

### Hardware

You will need one set of hardware per player, so for example if you have two tag players you will need to double the kit quantities on this list.

We used the [MonkMakes clever card kit](https://www.monkmakes.com/cck/){:target="_blank"} which contains all of the following components:

+ RFID tag reader
+ RFID tag or card
+ 7 female-female jumper leads
+ RGB LED with pre-attached jumper leads

Plus:

+ Raspberry Pi Zero or Zero-W
+ Male header and soldering iron to attach it OR [hammer header](https://shop.pimoroni.com/products/gpio-hammer-header){:target="_blank"}
+ USB battery pack

### Software

+ Python 3 (comes as standard with Raspbian)
+ SPI-Py

--- collapse ---
---
title: Install SPI-Py
---

+ Open a terminal and make sure you are in the `/home/pi` directory by typing `cd /home/pi`.

+ Install SPI-Py by typing the following commands, each followed by <kbd>Enter</kbd> on the keyboard.

```
git clone https://github.com/mab5vot9us9a/SPI-Py  
cd SPI-Py
sudo python3 setup.py install
```

--- /collapse ---

+ MFRC522

--- collapse ---
---
title: Install MFRC522
---

+ Open a terminal and make sure you are in the `/home/pi` directory by typing `cd /home/pi`.

+ Install MFRC522 by typing the following command, followed by <kbd>Enter</kbd> on the keyboard.

```
git clone https://github.com/mab5vot9us9a/MFRC522-python.git && cd MFRC522-python
```

--- /collapse ---

+ SimpleMFRC522

--- collapse ---
---
title: Install SimpleMFRC522
---

+ Open a terminal and make sure you are in the `/home/pi` directory by typing `cd /home/pi`.

+ Install SimpleMFRC522 by typing the following command, followed by <kbd>Enter</kbd> on the keyboard.

```
wget https://raw.githubusercontent.com/simonmonk/clever_card_kit/master/SimpleMFRC522.py
```

--- /collapse ---

### Additional Resources

+ Old t-shirt or sports bib
+ Needle and thread
+ Glove
