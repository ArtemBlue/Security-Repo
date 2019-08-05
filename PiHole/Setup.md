# PiHole Setup 
### Get Started Here
1) https://www.smarthomebeginner.com/pi-hole-tutorial-whole-home-ad-blocking/
2) https://bendews.com/posts/implement-dns-over-https/
### Gravity/Blocklist Sources
##### Lists to get you started;
##### [The Big Blocklist Collection](https://firebog.net/)
##### [The Best Blocking Lists](https://discourse.pi-hole.net/t/update-the-best-blocking-lists-for-the-pi-hole-alternative-dns-servers-2019/13620)
##### [CHEF-KOCH's List](https://github.com/CHEF-KOCH/NSABlocklist)
# 
##### How to Add with Terminal/Shell
#
```
1) Placeholder
2) Placeholder
```
<details>
  <summary>Spoiler warning</summary>
  
  Spoiler text. Note that it's important to have a space after the summary tag. You should be able to write any markdown you want inside the `<details>` tag... just make sure you close `<details>` afterward.
  
  ```javascript
  console.log("I'm a code block!");
  ```
  
</details>
##### How to Add with Web Console
#
```
1) 
2)
```
### REGEX Sources
##### Lists to get you started;
##### [Reddit REGEX Megathread](https://www.reddit.com/r/pihole/comments/b3fj60/regex_megathread/)
#
##### How to Add with Terminal/Shell
#
```
1) 
2)
```
##### How to Add with Web Console
#
```
1) 
2)
```
### Safesearch Setup (Optional) - Used mostly for families
##### https://www.reddit.com/r/pihole/comments/82h77r/google_safesearch/
# 
# File Locations
- /etc/pihole/adlists.list (Blocklist Used for Gravity)
- /etc/pihole/regex.list  (Regex list Used for Algorithmic Blacklisting)
- /etc/hosts (Local Host File)
# Commands
##### https://docs.pi-hole.net/core/pihole-command/  
# 
### Cheat Sheet  
[Whitelist]  - Single or Multiple Addresses seperated by space
```
pihole -w domainaddress1.com domainaddress2.com
```
[Restart dnsmasq/FTL] - Restart Service if changes made directly *may take a couple minutes*.
```
sudo service pihole-FTL restart
```
[Status dnsmasq/FTL] - Check Status 
```
sudo service pihole-FTL status
```

### Commonly Used
Edit Blocklist	
```
sudo nano /etc/pihole/adlists.list
```
Edit Regex 
```
sudo nano /etc/pihole/regex.list 
```
Restart FTL
```
sudo service pihole-FTL restart
```

# Connect Tests
-  https://en.internet.nl/connection/f32fffe5e9cf4b358ed994f440552a0f/results
-  https://www.cloudflare.com/ssl/encrypted-sni/
-  https://1.1.1.1/help

# Credits
``` 
Multiple Sources 
```
