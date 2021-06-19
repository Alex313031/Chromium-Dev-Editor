# Chromium-Dev-Editor
Revived version of Chrome Dev Editor - Chromium-ified! (original chrome app-id >> pnoffddplpippgcfjdhbmhkofpnaalpg)

# Background
There are many sucky editors on the chrome web store.
The best are Text https://chrome.google.com/webstore/detail/text/mmfbcljfglbokpmkimbfghdkjmjhdgbg?hl=en , and Quantuum https://chrome.google.com/webstore/detail/quantum/hmnlklahndgbhdoclhdnoafhafbhmnkm?hl=en (GitHub is here for installation on non Chrome OS platforms. >> https://github.com/DenisDeveloper/Quantum )
However, there was one above all the rest, developed by the Chromium Devs, for the Chromium Devs. The link is still up on ChromiumOS's site >> https://www.chromium.org/chromium-os/developing-apps-on-your-chromium-os-device in the first listing. However it is a dead link. The github is archived, and is only at version 0.17, while the last version on the web store was 0.23.3550. Don't ask me why that is. I was able to source the .crx file from CRX4Chrome >> https://www.crx4chrome.com/apps/pnoffddplpippgcfjdhbmhkofpnaalpg/. So I downloaded it, extracted it, and tried it. It had some errors, and some bugs, but it worked on *ChromiumOS ver. 90.1* unlike the 0.17 version. I then got to work modifying the source code to update/fix/and "Chromium-ify it"

# My Changes
Manifest.json was modified to reflect permissions changes since 2019. App version and descriptions were added or modified. Then I went to work changing everything I could that said Chrome/ChromeOS into "Chromium/ChromiumOS", except for non-ui things needed for compatability and functionality related to integration and centering around developing Chrome Apps ("Chromium Apps"). While searching the app-id on google, I also stumbled across a custom logo someone made for the app "EVO Numix Dock Theme Rocket Nexus Dock, ikon chrome-pnoffddplpippgcfjdhbmhkofpnaalpg-Default_192x192 png" - I might use that to change the default "chrome colored logo"

# But why??
Because I love Chromium, Chromium OS, derivatives like cloudready, wayne os, fydeos. And I hate Google's lately questionable morals. The straw that broke the camels back was when Google restricted apis used for signing in and syncing in chromiumos and chromium and chromium based browsers, because some third party browsers were using sync to sync settings. God forbid they lose a cent in revenue from people using api keys for their OPEN SOURCE PROJECT (supposed to be). After much strugle I was able to make my own private api keys to allow sign in on windows, and my own chromiumos builds and arnold the bats and wayne os builds. But that can only be used for one person after a lot of technical fuckery that took me a long time to figure out, even though I had previously made api keys for my own chromiumos builds. So to vent, im taking one of their really good, strangely abandoned projects, and modifying it to make it work on modern chromium and with as much googleness as possible removed. LONG LIVE FOSS!
And I feel for the linux community. Some distros like fedora and arch were even considering removing chromium from their repos altogether. And ive seen (and answered) peoples questions on the chromium-dev group forum, where people were frustrated and sad and clueless, getting halfway but getting stuck on making their own api keys and enabling them.

# Usage
I have included the original .crx, the original .crx extracted, the new logo, my own modifications in folder form, and finally the new crx packed and signed by me.

For regular usage download the .crx (hopefullu mine), go to chrome://extensions, enable developer mode in the upper right hand corner, then simply drag and drop the .crx, and it will install like any other chrome web store app.
