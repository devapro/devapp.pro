---
title: Certbot (setup ssl)
date: 2020-03-01 00:30:54
categories:
- Linux
tags:
- nginx
- ssl
---

## Quick Start

### Install Certbot 

`wget https://dl.eff.org/certbot-auto
sudo mv certbot-auto /usr/local/bin/certbot-auto
sudo chown root /usr/local/bin/certbot-auto
sudo chmod 0755 /usr/local/bin/certbot-auto`

### Either get and install your certificates

`sudo /usr/local/bin/certbot-auto --nginx`

### Just get a certificate 

`sudo /usr/local/bin/certbot-auto certonly --nginx`