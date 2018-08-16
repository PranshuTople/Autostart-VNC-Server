# Autostart VNC Server
Autostarting VNC Server in Raspberry Pi running Raspbian OS

When you are new to ***Raspberry Pi***, but don't have enough resources like HDMI Display, Spare USB Keyboard & Mouse, it often creates a problem to do ***Headless Setup***. But even after doing the setup, if you need to access the Raspberry Pi, you need to go through a long procedure of starting ***PuTTY*** on your Windows machine, starting ***VNC server*** through Pi Terminal and then accessing it through ***VNC Viewer***. In this Tutorial i would explain how you can autostart VNC server on Raspberry Pi, so all you need to do to access your Pi is ***Plug it to Power Supply*** and ***Open VNC Viewer***...

**That's It!!! DONE!!! That's all you need to do.**

## So here is how you can do it...

### Pre Requirements:
So this Tutorial Assumes that you have...
  * A Raspberry Pi running Raspbian OS.
  * Already done the Headless Setup.
  * Already installed VNC Server in the Raspberry Pi.

### Procedure:
  * Clone the repository to your Raspberry Pi by running the following command in your Pi's terminal
     
     ```
     git clone https://github.com/SaturnRobolabs/Autostart-VNC-Server
     ```
     
  * Copy the ***"tightvnc.desktop"*** file to ***"home/pi/.config/autostart"*** directory in the Pi.

UPDATES COMING SOON >>>
