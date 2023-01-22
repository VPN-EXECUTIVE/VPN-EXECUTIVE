### VPN-EXECUTIVE/AUTOSCRIPT
### Command Installing
### Update Server
```
apt update && apt upgrade -y --fix-missing && sleep 2 && reboot
```
### INSTALL
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://github.com/VPN-EXECUTIVE/VPN-EXECUTIVE/raw/main/vpn-executive.sh && chmod +x vpn-executive.sh && ./vpn-executive.sh
```

### VPN-EXECUTIVE SINCE 2010
