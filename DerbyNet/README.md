# Derbynet
> last updated February, 2024

Derbynet is an open source, multi-platform race coordination software. It's last known home was here: https://www.derbynet.org/
Derbynet is installed on a Raspberry Pi device. Generic documentation is below followed by specific setup details for our implementation.

## Files included in this directory

### Derbynet-Raspian-install-guide.pdf 
This is the official guide for installing the Derbynet software onto a RaspberryPi.
> https://derbynet.org/builds/Installation-%20Debian.pdf


## Pack 825 Custom Installation

### Raspberry Pi Setup
Download and install the Raspberry Pi Imager from the official Raspberry Pi homepage onto your local computer.  https://www.raspberrypi.com/software/

Using the Imager and a microSD card (plus adapter if needed), image the microSD card with an installation of the RaspPi 64-bit OS

Use custom settings to define the hostname, wifi (the imager should pull in your local wifi settings automatically), and default username and password.

Use either an attached keyboard/mouse/monitor or ssh to connect to your raspberry pi to complete the setup, install latest versions of all of the software, and preferably enable the VNC server so you can use RealVNC to connect remotely to the pi for configuration and troubleshooting.

### Installing Derbynet

You can use the above-mentioned guide for the installation. I highly recommend double-checking the website for derbynet to see if there have been any recent changes as new installations will get the latest version of derbynet.

The derbynet site has all of the guides for running a race (the latest versions have been added to this repository). https://derbynet.org/builds/docs.php



