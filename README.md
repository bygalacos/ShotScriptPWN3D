# ShotScriptPWN3D

Releasing all files that Shot Script uses & downloads.

Basicly using this script will compromise your system & data, due to encrypted bash code and you have to login as root to run script. Yeah even your passwd could be changeable ;)

##### NOTE THAT: 

This repository is entire clone of Shot Script script&file servers. 

You can clone everything except README.md to use script without any connection to Shot Script servers.
 
#### Redirect nexpanel.site to YOURIP or YOURSITE and be sure directory structure is correct with my repo. Put all files at / on webserver.

#### They still changing your hosts file to remove their block but im sure you will find a way (like i do).

## More Deep

They compiled every bash file to obfuscate their code.

So how to do?

#### Long story short. Mark them as executable first.

| Script Name  | Run Command  | Description |
| :------------ |:---------------:| ----- |
|anamenu|./anamenu|Main Menu|
|anasec|./anasec|Options|
|gamecontrol|./gamecontrol|Control Games|
|gameinstall|./gameinstall|Install Games|
|kurulumenu|./kurulumenu|Installation Menu|
|blacklistpatch|./blacklistpatch|SinusBot Patch|

ALERT: Shot & anamenu does lot of sensitive info (of yours) transfer with nexpanel.site . Redirect them to be %100 safe.

## Whats going on ??

Simple, they check ur data.

Log of Shot Script :

```
curl -s https://nexpanel.site/date.php
curl -s -4 https://nexpanel.site/ip.php

mkdir /home/shot/ads
cat /etc/hosts
grep shot.yasin.network
curl -s --head --request GET http://nexpanel.site/
clear
curl -N -s -4 --data secretkey=shotlist1453&islem=surum&version=8.0 http://nexpanel.site/settings/shotfunc.php
curl -N -s -4 --data secretkey=shotlist1453&islem=bakim&ok=ok http://nexpanel.site/settings/shotfunc.php
curl -N -s -4 --data ip=0.0.0.0&secretkey=shotlist1453&islem=lisans http://nexpanel.site/settings/shotfunc.php
curl -N -s -4 --data ip=0.0.0.0&secretkey=shotlist1453&islem=blacklist http://nexpanel.site/settings/shotfunc.php
rm -rf /usr/lib/scroll
cd /usr/lib/scroll
nohup curl --data ip=0.0.0.0&type=join https://nexpanel.site/????/????.php
curl --data ip=0.0.0.0&type=join https://nexpanel.site/????/????.php

clear
curl -s --head --request GET https://nexpanel.site/Script/Bildiriler/0.0.0.0.php
curl -s --head --request GET https://nexpanel.site/Script/Bildiriler/allip.php

```

# COURTESY OF BYGALACOS


## License
I dont have any, like they dont...
