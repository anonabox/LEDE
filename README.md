# lede
LEDE firmware sourcecode for development. 
This is a plain vanilla firmware for developers who prefer the lede fork of openwrt with the Anonabox Pro firmware patch applied. 
Sourcecode of the patch itself is included in the root directory in a file named anonabox_pro.patch for reference

Build Instructions:
1) git clone this repo into your local folder
2) make menuconfig
3) Select 'Target Profile'
4) Select 'Anonabox Pro' from the list
5) save and exit menuconfig
6) make

Feel free to customize as you see fit. Have fun!
You can flash the image using the admin interface from the default firmware. 



