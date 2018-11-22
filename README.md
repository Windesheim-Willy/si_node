# Social interaction node

## Installation on a Raspberry PI

### Install Raspbian
<https://www.raspberrypi.org/downloads/raspbian/>

### Enable SSH and VNC

1. Enter `sudo raspi-config` in a terminal window
* Select Interfacing Options
* Navigate to and select SSH
* Choose Yes
* Select Ok
* Navigate to and select VNC
* Choose Yes
* Select Ok
* Choose Finish

### Install Software

```
cd /opt
sudo git clone https://github.com/fabianvdbor/pi3_si.git willy
cd willy
sudo git checkout feature/infrastructure # TODO remove
sudo ./INSTALL
```
