# Browser_tracking_prevention

__Online finals is near and the profs are watching__ 

__This only works with Firefox version 71+__

If you are using Firefox as a default browser and don't want to mess with the default configuration 
you can use a different version of firefox ex: FF Nightly (linked below).

__May start auto download__
https://download.mozilla.org/?product=firefox-nightly-stub&os=win&lang=en-US

__Try this__
https://www.mozilla.org/en-US/firefox/channel/desktop/

Recommended Firefox (or Chrome if that's your thing) Extensions: 
- Ublock Origin
- HTTPS Everywhere _This may already be built in the latest version of FF_
- Decentraleyes
- ClearURLs
- Firefox Multi-Account Containers __May cause page to load slower but isolates Canvas__ 

__The information provided is a slimmed down version of what can be found at:__
https://www.privacytools.io/browsers/#about_config
Visit the site for more information on if to learn what what is being changed. 

## From the [privaytools.io guide](https://www.privacytools.io/browsers/#about_config)##

1. Enter "about:config" in the firefox address bar and press enter.
2. Press the button "Accept the Risk and Continue" [FF71+] or "I accept the risk".
3. Follow the instructions below...

__Using the "Search Preference" bar__
- privacy.firstparty.isolate = true  (Don't do this if you are using the Firefox Addon "Cookie AutoDelete" with Firefox v58 or below.)
- privacy.resistFingerprinting = true
- privacy.trackingprotection.fingerprinting.enabled = true
- privacy.trackingprotection.enabled = true
- browser.send_pings = false
- dom.event.clipboardevents.enabled = false __Disable that websites can get notifications if you copy, paste, or cut 
something from a web page, and it lets them know which part of the page had been selected.__
- media.navigator.enabled = false
- webgl.disabled = true (This may cause site breakage that has a lot of animations... not Canvas)
- browser.sessionstore.privacy_level = 2
- beacon.enabled = false __Disables sending additional analytics to web servers.__
- network.IDN_show_punycode = true

## Other Methods ##
- Use a second device to look at your notes
- Screenshots don't help unless there are texts next to it so you can index your notes faster (CTRL+F, MAC+F)
- Last resort... a virtual machine so you can keep the exam browser open and focused (only if you have a fast computer) a second mouse/KVM migh help with the mouse issue. 
