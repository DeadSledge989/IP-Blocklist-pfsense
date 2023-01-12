# IP Blocklist
## Description
IP blocklist of suspicious IP's
Should be different ip's as most list as this one is created by myself by own experiences

## How to use
You can import this list into PfSense using firewall > aliases > URLs
Then add a Block firewall rule using this alias
* https://github.com/DeadSledge989/IpBlocklist/blob/main/Blocklist.txt

Reason to use firewall > aliases > URLs (it auto updates every day, if the list gets updated)

## Other Usefull Links
### Spamhaus
* https://www.spamhaus.org/drop/drop.txt
* https://www.spamhaus.org/drop/edrop.txt
* https://www.spamhaus.org/drop/dropv6.txt

### BL_3coresec
* https://blacklist.3coresec.net/lists/all.txt

### BL_abusech_feodo_botnet_c2
* https://sslbl.abuse.ch/blacklist/sslipblacklist.txt
* https://feodotracker.abuse.ch/downloads/ipblocklist_recommended.txt

### BL_cins_army
* https://cinsscore.com/list/ci-badguys.txt

### BL_cisco_talos
* https://talosintelligence.com/documents/ip-blacklist

### BL_dshield_30d
* https://iplists.firehol.org/files/dshield_30d.netset