---
layout: post
title:  "Run interactive docker container"
date:   2016-11-15
categories: docker run interactive
---

You can attach to standard input of the process in the container and interact with it, just like a normal process.

In order to do that you need to pass `-i` or `--interactive` argument to `docker run` command:

    $ docker run -i busybox cat

After running the above command which basically runs `cat` inside the container whatever you type at the terminal will be echoed back to you.

To exit the container simply press Ctrl-D
