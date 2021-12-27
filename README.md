# ArchBaseInstall
 Arch linux base install script

# Check if the wifi devices are blocked.
```
rfkill list
```
# Turn Them on.
```
rfkill unblock all
```

# Connect To wifi
```
device list
```
#device is name of device
```
station device scan
station device get-networks
station device connect SSID
```
# References For help
https://wiki.archlinux.org/title/Network_configuration/Wireless

https://wiki.archlinux.org/title/Iwd
