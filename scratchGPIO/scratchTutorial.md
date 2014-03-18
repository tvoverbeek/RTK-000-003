Scratch GPIO Tutorial
============
This guide will walk you through the instructions to configure your Raspberry Pi with ScratchGPIO & VNC, then Program up your robot using ScratchGPIO software.

The configuration stage is best performed by a person who has basic skills with using the command line. Once configured any age should be able to do the Programming with Scratch stage.

Configuration
--------------
###Pre Configuration
Your SD card should already be configured to the guide "raspberryPiSetup.md" located in the top folder. This will have your Raspberry Pi configured for use on a wireless connection, you may find for the installation of the software plugging in a wired ethernet connection may speed parts of this installtaion.

Next you will need to connect to your Raspberry Pi via an SSH Client. Details on how to connect can be found in the "handyTipsGuides" folder under "sshConnection".


###Scratch GPIO
Now we need to install scratch, first start by downloading the installer by using the command
'''
wget http://goo.gl/Pthh62 -O isgh5.sh
'''
This will download the installer for ScratchGPIO V5. Next install it by running the following command:
'''
sudo bash isgh5.sh
'''

This will then install ScratchGPIO for you, after it says "Finished" you have now finished installing ScratchGPIO!


###VNC
VNC or Virtual Network Computing is an method we can use to be able to run a Virtual Desktop on the Raspberry Pi and use it over the network. This is now used commonly in day to day computing for cloud services or remote assitance.

For this part we will be installing a VNC server allowing your other computer to connect to the Raspberry Pi.

*NOTE* a VNC server on a Raspberry Pi will not reduce network security unless you allow people manually via a method called Port Forwarding. You will also setup a Password that is required to login to the Raspberry Pi.

First start by installing the tightvnc server using the command:

'''
sudo apt-get install tightvncserver
'''

Next we want to configure the server and add a password. Do this by typing in the command

'''
tightvncserver
'''






Programming with Scratch
--------------


---------------------------------------
Scratch GPIO is created by Simon Walters, Scratch is a project of the Lifelong Kindergarten Group at the MIT Media Lab.
Thanks to Penguin Tutor for letting me base the VNC installation off of his tutorial at http://www.penguintutor.com/linux/tightvnc




