---
layout: post
title:  "Run container with RKT"
categories: rkt run
---

Using Rkt is very similar to other container engines like Docker, once you have Rkt installed (just the binary, Rkt is daemon less) you can run your first container like this:

    # rkt --insecure-options=image run docker://hello-world

Notes:

* See how we specify docker images. If you are using images from Rkt image repos you can skip the protocol like: `coreos.com/etcd:v2.2.5`
* For Docker images we need to specify `--insecure-options=image` since Docker images do not support image signature verifications.

You should see something like this in output *Hello Docker because the image is from Docker hub :)*:

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

That's it. You've just executed your first Docker image with Rkt engine.

