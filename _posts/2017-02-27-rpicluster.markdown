---
layout: post
title: rpicluster
category: posts
---
*An rpicluster is a distro for a cluster of Raspberry Pis. rpicluster easily integrates a real cluster of computers, removing the hassle of networking and remote procedure calls. Downloadable images come with a set of tools to aid setup, configuration, and updates. The scalable architecture allows anyone to effortlessly put together a cluster and start creating their very own distributed/parallel projects. Visit this [link](http://www.rpicluster.com) to download the images and for more details.*

Instead of an internship, I invested my time into a big project for the summer. The goal was relatively simple: create a Raspberry Pi Cluster that is easily distributable. We demoed the projet many times at research events and garnered some attention and won a couple of awards. Eventually, we wanted to see how far it would go as a startup. What if we made a package that just did all the configuration? What if we extend this onto other IoT devices? What if we became millionaires? You know what it became? It became a dream that slowly deterioted because we also forgot that we were unemployed living with our parents.

The project presented some interesting questions during the development phases.

**1) How do you run python scripts to build scripts and package an image without unzipping the zip file first?**

Turns out there's a great tool created by the Raspberry Pi Foundation: [pi-gen](https://github.com/RPi-Distro/pi-gen). A fork of this repo allowed us to modify the images to create either an rpicluster server or node image file.

**2) How do you network the Pis together to create a scalable cluster? How do we discover the nodes intuitively?**

Managing the nodes to support multiple different networking capabilities adds complexity, and turned out to be a huge headache to implement. We eventually designed the startup process to include a neutral network before allowing the user to select their desired network. A reboot was necessary to ensure the right services started and IPtables were configured correctly.

Files were a little easier with a network up and running.

**3) How do I make my WiFi-based cluster unique to another network?**

We used a stamping mechanism in the images unique with their username and password of their WiFi network and passing the lengths into a build.

The images turned out a small (< 5GB total!), efficient, and usable, so that was a pleasant experience . One day I hope to return to this project.

Take a look at the project if you want:
[rpicluster][rpicluster]

---

Talk to me.

[messenger][facebook]

[github][dqd]

[reddit][reddit]

[PGP][PGP]

[facebook]: https://www.m.me/dqdang1
[dqd]: http://github.com/dqdang
[reddit]: https://www.reddit.com/user/outsidefarmland/
[PGP]: http://www.dqdang.github.io/derek-dang.asc
[rpicluster]: https://github.com/rpicluster/rpicluster-stretch
