# RPi WS281x Python

This is the official Python distribution of the ws281x library: http://github.com/richardghirst/rpi_ws281x

# Installing

## Setup your own environment from pip

Most users should simply run:

```
sudo pip install rpi_ws281x
```

## Lights (what we have)

https://www.amazon.com/INVOLT-Individually-Addressable-Programmable-Decoration/dp/B07GKWCFG3

## IP
```sh
#password is raspberry
ssh pi@192.168.165.101
```
## Editing the lights and running your code

```sh
#COPY THE BASE
cp ~/rpi-ws281x-python/run/1.py ~/rpi-ws281x-python/run/yourcode.py
#EDIT YOURS
vi ~/rpi-ws281x-python/run/yourcode.py
#Kill the running process
sudo killall python
#RUN YOURS
sudo python ~/rpi-ws281x-python/run/1.py
```

## Root Crontab (change the default on reboot)

```sh
sudo crontab -e
#Change this line
#@reboot python /home/pi/rpi-ws281x-python/run/yourcode.py
```
