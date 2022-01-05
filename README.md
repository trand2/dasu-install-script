# Dasu
DIY NFT Art Display

# Steps to use
1. Install the Raspbian operating system onto the SD card
https://www.raspberrypi.org/downloads/raspbian/

2. Insert the SD card, keyboard, and monitor and boot up your Raspberry Pi

3. Upon boot up the OS should prompt you to configure the wifi network and install updates.

4. You can adjust the resolution by opening the start menu, select Preferences, Raspberry Pi Configuration

5. Run the following script to install Dasu:
`sudo bash -c "$(curl https://raw.githubusercontent.com/trand2/dasu-install-script/master/install.sh)"`

6. The Raspberry Pi will reboot for settings update to take effect and should automatically start Dasu on reboot
