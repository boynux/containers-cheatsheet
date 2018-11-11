---
layout: post
title:  "Install RKT on Linux"
date:   2016-11-14
categories: rkt linux install
---

RKT (read Rocket) is a secure and versatile pod-native container engine created by [CoreOS](https://github.com/rkt/rkt). Rkt works very will with Linux `init` systems like `systemd`. It's daemon-less but can utilize API servers for interactions with other services.

For Debian based distros use:

    sudo apt-get install rkt

For RPM based distros:

    sudo dnf install rkt

More options and documentation is [here](https://github.com/rkt/rkt/blob/master/Documentation/distributions.md)

Various packaging options and binary downloads can be found in [Github](https://github.com/rkt/rkt/releases)

