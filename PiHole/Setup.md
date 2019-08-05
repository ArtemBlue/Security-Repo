# PiHole Setup
- Multiple Sources
# Setup Links
### Get Started Here
1) https://www.smarthomebeginner.com/pi-hole-tutorial-whole-home-ad-blocking/
2) https://bendews.com/posts/implement-dns-over-https/
### Safesearch Setup (Optional) - Used mostly for families
##### https://www.reddit.com/r/pihole/comments/82h77r/google_safesearch/
# 
### REGEX Lists
##### https://www.reddit.com/r/pihole/comments/b3fj60/regex_megathread/
# 
# File Locations
- /etc/pihole/adlists.list (Blocklist Used for Gravity)
- /etc/pihole/regex.list  (Regex list Used for Algorithmic Blacklisting)
- /etc/hosts (Local Host File)
# Commands
##### https://docs.pi-hole.net/core/pihole-command/  
# 
### Cheat Sheet  
* [Whitelist]  - Single or Multiple Addresses seperated by space
`pihole -w domainaddress1.com domainaddress2.com`
* [Restart dnsmasq/FTL] - Restart Service if changes made directly *may take a couple minutes*.
`sudo service pihole-FTL restart`
* [Status DNSMasq/FTL] - Check Status 
`sudo service pihole-FTL status`

### Commonly Used
* Edit Whitelist	
`sudo nano /etc/pihole/adlists.list`
* Edit Regex 
`sudo nano /etc/pihole/regex.list`
* Restart FTL
`sudo service pihole-FTL restart`

# Connect Tests
-  https://en.internet.nl/connection/f32fffe5e9cf4b358ed994f440552a0f/results
-  https://www.cloudflare.com/ssl/encrypted-sni/
-  https://1.1.1.1/help

