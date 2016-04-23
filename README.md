# Introduction

This is a quick and dirty explanation for myself on how to do a bare bone installation of my favorite pinball tables on a freshly new installation of Windows 10.

Requisites (my setup):

* PC, Intel Core i5-6600K CPU@3.50GHz, 8GB RAM, 128GB SSD Drive
* LEDWiz controller (https://shop.strato.de/epages/64158583.sf/sec719530a4a3/?ObjectPath=/Shops/64158583/Products/50007)
* Arcade-mame DIY Kit for 2 players (http://www.aliexpress.com/item/Arcade-mame-DIY-KIT-FOR-2-players-PC-PS-3-2-IN-1-to-arcade-joystck/32595240925.html)
* 2 Screens, 1 x Philips BDM4065UC (40", 3840 x 2160 Pixel @ 60Hz), 1 x Dell UltraSharp U2713HM (27", 2560 x 1440 Pixel)

# Windows

* I am using Windows 10

## Auto login

* Run -> netplwiz
* A User Accounts window will open. Under Users for this computer: select your username and then uncheck the box next to Users must enter a user name and password to use this computer. Click Apply.
* A new window labeled Automatically sign in will pop up. Type your password twice and then click OK.

Your computer will now bypass the log-in page when you turn on your PC, but it will not bypass the login page when you unlock your PC. You can also change your sign-in options so that Windows will never require you to sign in after your PC wakes from sleep by going to Settings > Accounts > Sign-in options.

References:

* http://www.cnet.com/how-to/automatically-log-in-to-your-windows-10-pc/

## Auto start PinballX

* Run -> shell:startup
* Paste the icon for the starutp of PinballX into the explorer window

* http://www.howtogeek.com/208224/how-to-add-programs-files-and-folders-to-system-startup-in-windows-8.1/


# LedWiz

* Arduino clone: http://www.vpforums.org/index.php?showtopic=26043&hl=arduino
* 
# References

* http://configtool.vpuniverse.com/
* http://directoutput.github.io/DirectOutput/index.html
* http://vpuniverse.com/forums/files/file/437-pinball-electrical-101/

* https://github.com/NicoHood/HID
* http://www.ledblinky.net/LEDBlinky.htm

Cool projects to follow:

* Mini cabinet, good description on how to create your own Arduino based tilt sensor: https://hackaday.io/project/5154/logs
