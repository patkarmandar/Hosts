# Hosts

Bash script to create unified host file from multiple sources.

## Script Configuration :

- `LOCAL_HOST` : local server to which request is redirected, set to `0.0.0.0` or `127.0.0.1` (default is `0.0.0.0`)
- `OUTPUT_HOST` : output hosts-styled blocklist (default is `hosts.txt`)
- `source.list` : plain text file from which hosts-styled sources is to be fetch
- `source.domain` : plain text file from which only ip/domain sources is to be fetch

**NOTE -**
- `source.list` : should have only host-styled format sources, Ex- `0.0.0.0 www.example.com`
- `source.domain` : should have only ip/domain format sources, Ex- `www.example.com`

**To add local blocklist use `file://` URL**

- Add hosts sources/links in `source.list` and `source.domain`, remember above noted points.
- Add one source/link at each line
- If list has only one entry then add extra empty line at end *(some issue with curl)*
- Run `script.sh`

*(run script in empty folder to avoid issues)*


<br>

## Hosts Lists :

Curated and well-maintained hosts files to block social media, trackers, porn sites &amp; ads.

| Hosts | Contains | RAW Links |
| --- | --- | --- |
| Porn | Porn Sites + Pornaway's Porn Sites + Porn Ads | [link](https://raw.githubusercontent.com/patkarmandar/hosts/main/porn.txt) |
| Extreme | miui and microsoft's windows trackers + reporting domains + WebRTC Trackers + Canvas Fingerprinting Pages + Canvas Font Fingerprinting + Audio Fingerprinting + NSA Blocklist | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/extreme.txt) |
| China | wechat, weibo, qq, yy, renren, baidu | [link](https://raw.githubusercontent.com/patkarmandar/hosts/main/china.txt) |
| Annoyance (My Personal Hosts) | refer hostlist | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/annoyance.txt) |

*Note: Extreme hostlist may break some pages.*


## Extensions :
| Hosts | RAW Links |
| --- | --- |
| Facebook | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/Extensions/facebook.txt) |
| Google | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/Extensions/google.txt) |
| Instagram | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/Extensions/instagram.txt) |
| Linkedin | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/Extensions/linkedin.txt) |
| Pinterest | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/Extensions/pinterest.txt) |
| Reddit | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/Extensions/reddit.txt) |
| Snapchat | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/Extensions/snapchat.txt) |
| Telegram | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/Extensions/telegram.txt) |
| Tiktok | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/Extensions/tiktok.txt) |
| Twitter | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/Extensions/twitter.txt) |
| WhatsApp | [link](https://raw.githubusercontent.com/patkarmandar/Hosts/main/Extensions/whatsapp.txt) |


## Credits For Sources :
- [Steven Black Hosts](https://github.com/StevenBlack/hosts)
- [Pornaway](https://github.com/mhxion/pornaway)
- [Fanboy Hosts](https://www.fanboy.co.nz)
- [Energized.pro](https://energized.pro)
- [LukeSmithxyz Hosts](https://github.com/LukeSmithxyz/etc)
- [CHEF-KOCH' NSABlocklist (Repo Closed)](https://github.com/CHEF-KOCH/NSABlocklist)
- [Cauchon' NSABlocklist-Pi-Hole-Edition](https://github.com/Cauchon/NSABlocklist-pi-hole-edition)
