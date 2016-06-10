OS setup
========

Intial setup
------------

1. Install Raspbian on SD card
2. Go through Raspbian setup
3. Connect to Wifi and log in via SSH:

        `ssh pi@192.168.178.***`

Password is `raspberry` by default.

4. Give the Pi a static ip address for convenience (in your router settings)
5. Update all programs and libraries:

        `sudo apt-get update` (update list of packages)
        `sudo apt-get upgrade` (update packages to new versions)

6. Install programs:

        `sudo apt-get install tightvnc-server vim python3 python3-pip`

7. Set up VNC:

        Guide here: https://www.raspberrypi.org/documentation/remote-access/vnc/

8. Log in via VNC, use the RPi's ip with port 5901 (i.e. 192.168.178.19:5901), to check if VNC works


Backing up your setup
---------------------

Once you've set up the Pi once, you'll want to make a backup of the
SD card so you can restore your Pi to this state in one go.
