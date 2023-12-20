# Ansible Role Nginx

This repository contains files and recipes to manange a nginx installation via 
Ansible on a Debian server.

In general this role allow to configure vhosts.

**NB:** this role relay on [ansible-common-role](https://github.com/stethewwolf/ansible-common-role)

## Installed packages

This role will install following packages:
```
  nginx
  certbot
```

## Firewall Configuration

### Iptables 
Using the variables 

```
enable_http: true # default enable
enable_https: false # defalut disable
```
You can control if open http and https ports on the iptables firewall

**TODO:** https management is not yet implemented

### Fail2Ban
***TODO*** 

## VirtualHosts
***TODO*** 

