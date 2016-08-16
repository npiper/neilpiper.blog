---
layout: post
title:  "Docker How-to"
date:   2016-08-20 01:19:39 +1000
categories: Docker containerisation 

---

# Running Docker in a less than perfect environment

Docker works great running on your direct connect to the internet powerful PC at home, where multiple teams and developers have gone awry is wrangling with putting the flexibility of Docker onto the constrained environment of most corporates with security & SOE:

* Proxy servers
* SSL sniffing
* Restricted networks
* Corporate SOE's with limited space, admin policies or default drive locations (non SSD)
* DNS Namespaces and name servers
* Anti-Virus software or external processes that interfere with VM
* Restrictive Admin policies that prevent installation of Network changes needed for VM's
* ..

## What version should I use?

At least 



## Behind a Proxy?

https://crondev.com/running-docker-behind-proxy/

### & on Windows?

http://toedter.com/2015/05/11/docker-on-windows-behind-a-firewall/

## Limited disk space - need to cleanup often?

Remove all images & containers - https://techoverflow.net/blog/2013/10/22/docker-remove-all-images-and-containers/


### Where to put VM Images?

Set a `VAGRANT_HOME` location - defaults to 'C:' drive

## DNS / Namespace issues?

Configure container DNS - https://docs.docker.com/engine/userguide/networking/default_network/configure-dns/

