# youtube_ios_adblock
add user customize domain to block ads in iOS youtube app


//20181031 
tested in 
- iOS 12.0.1 
- Youtube App version 13.42.6

step1:
download AdBlock in AppStore (https://www.adblockios.com/)

step2:
Settings -> Manage DNS rules -> (select any domain group list) -> +Add domains
Add the below domains 
1. partnerad.l.doubleclick.net
2. securepubads.g.doubleclick.net
3. ade.googlesyndication.com

This step will point those domain to 0.0.0.0 (loopback).

step3: 
remember to save the rules. 

step4 (optional)
Refresh the service by going back to app's front page and then 
slide down to disable , and then, slide up to enable 
OR
kill the AdBlock app and open the AdBlock app again.



Enjoy youtube without ads ~ 
