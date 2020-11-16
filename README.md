# RPi WS281x Python

This is the official Python distribution of the ws281x library: http://github.com/richardghirst/rpi_ws281x

# Installing

## From pip

Most users should simply run:

```
sudo pip install rpi_ws281x
```

## Lights

https://www.amazon.com/INVOLT-Individually-Addressable-Programmable-Decoration/dp/B07GKWCFG3

# IP

192.168.165.101

# Root Crontab

```sh
@reboot python /home/pi/rpi-ws281x-python/run/1.py
```
