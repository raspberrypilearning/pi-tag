## Test the RFID reader

Let's test that the RFID reader works properly.

+ Open the Raspberry Pi configuration menu

![Raspberry Pi config](images/rpi-config.png)

+ Make sure that SPI is enabled - this is how your RFID reader will talk to the Raspberry Pi.

![Enable SPI](images/enable-spi.png)

+ Reboot the Raspberry Pi.

+ Make sure you have installed the required software (see the "What you will need" step). You will notice that some extra folders have been created inside your `/home/pi` directory.

+ Open IDLE and create a new file called `rfid_test.py`, and make sure to save this file in the `clever_card_kit` folder.

[[[rpi-gui-idle-opening]]]


+ Write some code to test whether your RFID reader can read a tag

```python
import RPi.GPIO
import SimpleMFRC522


reader = SimpleMFRC522.SimpleMFRC522()

print("Hold a tag near the reader")

while True:
    id, text = reader.read()
    print(id)
    print(text)


GPIO.cleanup()
```
