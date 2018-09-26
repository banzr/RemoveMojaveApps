# RemoveMojaveApps
How to remove protected apps, such as News, Stocks, and Home from a Mojave macOS installation

### Special thanks to [9define](https://github.com/9define) for suggesting this workaround! :) 

## About
Have you upgraded to Majave on your mac and object to sponsored apps? Refuse to be pushed Apple's liberal News or to be shilled Apple's Home ecosystem of products? Hate the XNU kernel? Don't want to disable SIP just to nuke a few apps?

## Problem
![alt text](https://raw.githubusercontent.com/banzr/RemoveMojaveApps/master/screens/cant-delete.png)

## Reasons

* Stocks -- Streams CNBC echonomic news, which is a biased news outlet.
* News -- Multiple liberal sources. Biased. Little to no unfiltered conservative representation. Shills Apple products.
* Home -- Forces users to buy products that pay Apple for the priviledge of being compatible with macOS and iOS.

## Steps
1. Install/Upgrade to Mojave

2. Reboot into recovery mode. 
	* Shutdown your mac.
	* Hold `Command + R` and press power. Continue to hold the keyboard keys until the Apple logo and loading bar appears. 

3. Select Disk Utility from the list of options
![Recovery mode splash screen](https://raw.githubusercontent.com/banzr/RemoveMojaveApps/master/screens/recovery-mode-opts.jpg)

4. Select your MacOS Mojave installation disk on the left and click `Mount` on the top right.
![Disk utility select root drive](https://raw.githubusercontent.com/banzr/RemoveMojaveApps/master/screens/unmounted-root-drive.jpg)
![Disk utility mount root drive](https://raw.githubusercontent.com/banzr/RemoveMojaveApps/master/screens/mount-root-drive.jpg)

5. Close Disk Utility

6. Open Terminal by clicking `Utilities -> Terminal`

7. `cd /Volumes/<Mojave root disk>/Applications/`

8. `rm -rf {News.app,Home.app,Stocks.app}`

Results:
![Terminal output](https://raw.githubusercontent.com/banzr/RemoveMojaveApps/master/screens/terminal-ouput.jpg)

9. Reboot

10. Enjoy your new macOS without ads! :)
![App drawer](https://raw.githubusercontent.com/banzr/RemoveMojaveApps/master/screens/app-drawer.jpg)

