---
layout: post
title:  "Run your first Docker container"
date:   2016-11-14
categories: docker linux run
---

If you haven't installed Docker please look at the [previous post](/docker/linux/2016/11/14/install-docker-linux.html).

To run a Docker container you can execute the following command in terminal:

    $ docker run hello-world

You should shee something like this in output:

    Hello from Docker!
    This message shows that your installation appears to be working correctly.

    To generate this message, Docker took the following steps:

     1. The Docker client contacted the Docker daemon.
     2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
     3. The Docker daemon created a new container from that image which runs the
        executable that produces the output you are currently reading.
     4. The Docker daemon streamed that output to the Docker client, which sent it
        to your terminal.

    ...

That's it. You've just executed your first Docker container.

