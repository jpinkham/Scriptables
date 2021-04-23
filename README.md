# Scriptables
For use with iOS Scriptables app

[TODO] insert link to app store details

# Scripts

## Widgets

These generate a widget to use on home screen 

[TODO] link to  instructions on how to add

* whatismyip.js - shows the current ip your device appears as on the internet. Useful for  scenarios where you are behind any NAT device or using mobile carrier for internet access
    * WARN: the text font is white on a dark background, so you will not see much if you use iOS Light Mode. The text color is easy to customize within the script.
    * My use case: firewall with multiple vpnclient tunnels using multiple VPNs. i like to know which one my traffic is being routed through at any particular time
    * NOTE: powered by https://whatismyip.host

![Example (showing a VPN service ip)](images/screenshot_whatismyip.png)


* Pihole_simple_stats.js - barebones, widget size: small
    * Status -- "Enabled" in green text, all other values display in red
    * Queries count for today
    * Number ads blocked
    * Percentage ads blocked
    * Number of unique domains
    * Gravity DB age

![Example (showing stats from just 2 humans but a cacophony of IoT devices)](images/screenshot_pihole_simple_stats.png)


## not widgets

[TODO] Write some scripts that aren't widgets



# License
jpinkham/Scriptables is licensed under the GNU General Public License v3.0
