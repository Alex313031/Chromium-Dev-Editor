<img src="https://github.com/Alex313031/Chromium-Dev-Editor/blob/main/new_icon.png">

# Chromium Dev Editor
Revived version of Chrome Dev Editor - Chromium-ified! (original chrome app-id >> pnoffddplpippgcfjdhbmhkofpnaalpg)

# Background
There are many sucky editors on the chrome web store.
The best are Text https://chrome.google.com/webstore/detail/text/mmfbcljfglbokpmkimbfghdkjmjhdgbg?hl=en , and Quantuum https://chrome.google.com/webstore/detail/quantum/hmnlklahndgbhdoclhdnoafhafbhmnkm?hl=en (GitHub is here for installation on non Chrome OS platforms. >> https://github.com/DenisDeveloper/Quantum )
However, there was one above all the rest, developed by the Chromium Devs, for the Chromium Devs. The link is still up on ChromiumOS's site >> https://www.chromium.org/chromium-os/developing-apps-on-your-chromium-os-device in the first listing. However it is a dead link. The github is archived, and is only at version 0.17, while the last version on the web store was 0.23.3550. Don't ask me why that is. I was able to source the .crx file from CRX4Chrome >> https://www.crx4chrome.com/apps/pnoffddplpippgcfjdhbmhkofpnaalpg/. So I downloaded it, extracted it, and tried it. It had some errors, and some bugs, but it worked on *ChromiumOS ver. 90.1*, unlike the 0.17 version. I then got to work modifying the source code to update/fix/and "Chromium-ify it"

# My Changes
Manifest.json was modified to reflect permissions changes since 2019. App version and descriptions were added or modified. Then I went to work changing everything I could that said Chrome/ChromeOS into "Chromium/ChromiumOS", except for non-ui things needed for compatability and functionality related to integration and centering around developing Chrome Apps ("Chromium Apps"). While searching the app-id on google, I also stumbled across a custom logo someone made for the app "EVO Numix Dock Theme Rocket Nexus Dock, icon chrome-pnoffddplpippgcfjdhbmhkofpnaalpg-Default_192x192 png" - I might use that to change the default "chrome colored logo". UPDATE: Changed.

# But why??
Because I love Chromium, Chromium OS, and derivatives like CloudReady, WayneOS, FydeOS, and the like. And I hate Google's lately questionable ethics. The straw that broke the camel's back was when Google restricted APIs used for signing in and syncing in ChromiumOS and Chromium and Chromium based browsers, because some third party browsers were using sync to sync settings (what's wrong with that). The sucky explanation is here on the Chromium Blog >> https://blog.chromium.org/2021/01/limiting-private-api-availability-in.html God forbid they lose a cent in revenue from people using API keys for their OPEN SOURCE PROJECT (...supposed to be). After much struggle I was able to make my own private API Keys to allow sign in on windows, (linux builds have for most of my distro's I run, had the sign in code compeletely removed) and (especially) my own ChromiumOS builds and ArnoldTheBat's and WayneOS builds. But that can only be used for one person after a lot of technical fuckery that took me a long time to figure out, even though I had previously made API Keys for my own ChromiumOS builds. So to vent, I'm taking one of their really good, strangely abandoned projects, and modifying it to make it work on modern Chromium and with as much Google-ness as possible removed. LONG LIVE F.O.S.S.!
And I feel for the linux community. Some distros like fedora and arch linux were even considering removing Chromium from their repos altogether. And I've seen (and answered) people's questions on the chromium-dev group forum, where people were frustrated and sad and clueless, getting halfway but getting stuck (like I did) on making their own API Keys, enabling them, and using them on CrOS.

# Usage
I have included the original .crx, the original .crx extracted, the new logo/old logo, my own modifications in extracted folder form, and finally the new .CRX file packed and signed by me.

For regular usage download the .crx (hopefullu mine >> cros-editor.crx), go to chrome://extensions, enable developer mode in the upper right hand corner, then simply drag and drop the .crx, and it will install like any other chrome web store app.

# File Names
cros-editor.crx -- My .crx  
pnoffddplpippgcfjdhbmhkofpnaalpg-0.23.3550-Crx4Chrome.com.crx -- Original .crx  
cros-editor -- My .crx unpacked.  
original_crx -- Original .crx unpacked.  
new_icon.png -- New logo (integrated into both crx and unpacked extension).  
original_icon.png -- Original 256p logo.  
README.md -- This Readme markup doc.  

# Version History
0.23.03550 - Original Chrome App version  
0.23.03551 - My Chromium version  
0.23.03552 - Logo changed and version bump.  
