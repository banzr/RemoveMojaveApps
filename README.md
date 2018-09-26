# RemoveMojaveApps
How to remove protected apps, such as News, Stocks, and Home from a Mojave macOS installation

### Special thanks to @9define for suggesting this workaround! :) 

## About
Have you upgraded to Majave on your mac and object to sponsored apps? Refuse to be pushed Apple's liberal News or to be shilled Apple's Home ecosystem of products?

## Problem
![alt text](https://raw.githubusercontent.com/banzr/RemoveMojaveApps/master/Screenshot1.png)

## Reasons
Stocks -- Streams CNBC echonomic news, which is a biased news outlet.
News -- Multiple liberal sources. Biased. Little to no unfiltered conservative representation. Shills Apple products.
Home -- Forces users to buy products that pay Apple for the priviledge of being compatible with macOS and iOS.

## Steps
1. Install/Upgrade to Mojave

2. Reboot into recovery mode.

3. Open Disk Utility by clicking... `Utilities -> Disk Utility`

4. Select your MacOS Mojave installation disk on the left and clicking `Mount` on the top right.

5. Close Disk Utility

6. Open Terminal by clicking `Utilities -> Terminal`

7. `cd /Volumes/<Mojave root disk>/Applications/`

8. `rm -rf {News.app,Home.app,Stocks.app}`

9. Reboot

10. Enjoy your new macOS without ads! :)

