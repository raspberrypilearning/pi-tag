## Auto start on boot

Now that your tag game code works, you need to make it start automatically when the Raspberry Pi boots up as you don't want to have a screen, mouse and keyboard attached to your Pi when you are wearing it!

+ Open up a terminal window

+ At the terminal, type the following command:

```
sudo nano ~/.config/lxsession/LXDE-pi/autostart
```

+ A file will open up, add this line at the bottom of the file to automatically start the tag game code using Python 3:

```
sudo /usr/bin/python3 /home/pi/clever_card_kit/tag_game.py
```
+ Press <kbd>Ctrl+X</kbd> to exit and <kbd>y</kbd> to save the changes.

+ When you reboot your Raspberry Pi, the script should run. Note that when you reboot, Python will be running in the background. You will not see any window showing that your script is running. However, you should see the LED light up white when the game is ready to start.
