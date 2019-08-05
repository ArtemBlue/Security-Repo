# PiHole Setup
# Sources - Multiple;
#============================================================================
Setup Links;
1) https://www.smarthomebeginner.com/pi-hole-tutorial-whole-home-ad-blocking/
2) https://bendews.com/posts/implement-dns-over-https/
#============================================================================
Safesearch Setup
https://www.reddit.com/r/pihole/comments/82h77r/google_safesearch/
#============================================================================
Location of PiHole Files
/etc/pihole/
-  adlists.list (block list)
-  regex.list (regex list)
/etc/
-  hosts (host file)
#============================================================================
Commands
[Whitelist]: 		pihole -w domainaddress1.com domainaddress2.com
[Restart DNSMasq/FTL]: 	sudo service pihole-FTL restart
[Status DNSMasq/FTL]: 	sudo service pihole-FTL status

Commonly Used
sudo nano /etc/pihole/adlists.list
sudo nano /etc/pihole/regex.list
sudo service pihole-FTL restart
#============================================================================
#Connect Tests
-  https://en.internet.nl/connection/f32fffe5e9cf4b358ed994f440552a0f/results
-  https://www.cloudflare.com/ssl/encrypted-sni/
-  https://1.1.1.1/help

