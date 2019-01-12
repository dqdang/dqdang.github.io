---
layout: post
title: rpicluster
category: posts
---
*This is a user-friendly implementation of [Raspberry Pi](https://www.raspberrypi.org/) Clusters. A rpicluster easily integrates a real cluster of computers, removing the hassle of networking and remote procedure calls. The images come with a set of tools to aid setup, configuration, and updates. The scalable architecture allows anyone to effortlessly put together a cluster and start creating their very own distributed/parallel projects. Visit this [link](www.rpicluster.com) to download the images and for more details.*

Instead of a valuable internship, I invested my youth into a big project for the summer. The goal was relatively simple: create a Raspberry Pi Cluster that is easily distributable. We demoed the projet multiple times at research events and garnered some attention. Eventually, we wanted to see how far it would go as a startup. What if we made a package that just did all the configuration? What if we extend this onto other IoT devices? We could've taken that risk. But we also forgot that we were unemployed with empty pockets.

The project presented some interesting questions during the development phases.

**1)** How do you run python scripts to build scripts and package an image without unzipping the zip file first?

Turns out there's a great tool created by Raspberry Pi: [pi-gen](https://github.com/RPi-Distro/pi-gen). A simple fork of this repo allowed us to modify the images to create either a server or node .img.

**2)** How do you network the Pis together to create a scalable cluster? How do we discover the nodes intuitively?

Managing the nodes to support multiple different networking capabilities adds complexity, and turned out to be a huge headache to implement. We eventually designed the startup process to include a neutral network before allowing the user to select their desired network. A reboot was necessary to ensure the right services started and IPtables were configured correctly.

**3)** How do I make my WiFi-based cluster unique to another network?

This led to a requirement for users to "stamp" their images with their username and password of their WiFi network and passing the lengths into a build.

The images turned out a lot smaller than expected, so that was a pleasant surprise. One day I hope to return to this project.

---

Take a look at the project if you want:
[rpicluster][rpicluster]

Talk to me.

[messenger][facebook]

[github][dqd]

[reddit][reddit]

[facebook]: https://www.m.me/dqdang1
[dqd]: http://github.com/dqdang
[reddit]: https://www.reddit.com/user/outsidefarmland/
[rpicluster]: https://github.com/rpicluster/rpicluster-stretch
