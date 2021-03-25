Instructions for MacOS:
Go to https://www.charlesproxy.com/download/ and download latest release for Mac OS.
Install as per instructions on your machine.
Open Charles, Go to Settings → Recording Settings → Include tab to filter irrelevant data.
For example, *.broadaxec3.com, *.locushealth.dev, durin.intng.locushealth.dev
Go to Proxy → SSL Proxying Settings → SSL Proxying
Check "Enable SSL Proxying" and enter locations to be proxied.
For example, *.example.com, *.dev.example.org

Instructions for iOS:
Go to Device Settings → Wifi, make sure device under test is on same wifi as Mac OS.
Select Wifi Network → HTTP Proxy → Configure Proxy. Configure your device to use Charles as its HTTP proxy Mac OS's IP:8888.
Open Safari browser, go to chls.pro/ssl to download and install the certificate. 
Follow prompt on screen,
For iOS 10 and above, go to Settings → General → About → Certificate Trust Settings and enable the Charles certificate to be trusted. 

Useful Features:
Breakpoints Tool: https://www.charlesproxy.com/documentation/proxying/breakpoints/
Map Local Tool: https://www.charlesproxy.com/documentation/tools/map-local/
Rewrite Tool: https://www.charlesproxy.com/documentation/tools/rewrite/
Bandwidth Throttle / Bandwidth Simulator: https://www.charlesproxy.com/documentation/proxying/throttling/

Gotchas!
Remember to turn charles proxy off on the device under test after use, otherwise be prepared for wonky test results. 
Remember to turn Breakpoint / Map Local / Rewrite tools off after user, otherwise be prepared for wonky test results. 
