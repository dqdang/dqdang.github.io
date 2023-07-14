---
layout: post
title: dev environment
category: posts
---

*Set of environment scripts for future reference*

I have a couple scripts to recreate a development enviroment I'm comfortable with.

Dev environment are always a huge hassle when migrating from computer to computer, so keeping organized alleviates the onboarding process.
<br/>

This is what my directory tree of my Windows environment looks like:
~~~
C:
└───git
    │
    └───folder1
    │      │   README.md
    │      │   file012.txt
    │      │
    │      └───subfolder1
    │          │   file111.txt
    │          │   file112.txt
    │          │   ...
    │
    └───folder2
           │   README.md
           │   file022.txt
    │
    │   ...
...
~~~
<br/>

This is what my directory tree of my Mac environment looks like:
~~~
Users
└───$USER
    └───git
        │
        └───folder1
        │      │   README.md
        │      │   file012.txt
        │      │
        │      └───subfolder1
        │          │   file111.txt
        │          │   file112.txt
        │          │   ...
        │
        └───folder2
            │   README.md
            │   file022.txt
        │
        │   ...
    ...
...
~~~
<br/>

This is what my directory tree of my Unix environment looks like:
~~~
home
└───$USER
    └───git
        │
        └───folder1
        │      │   README.md
        │      │   file012.txt
        │      │
        │      └───subfolder1
        │          │   file111.txt
        │          │   file112.txt
        │          │   ...
        │
        └───folder2
            │   README.md
            │   file022.txt
        │
        │   ...
    ...
...
~~~
<br/>

These are the scripts to get things going: [abode][abode]

Here's a script that takes the python directories in the git folder and installs their requirements: [updater][updater]

---

[discord][discord]

[github][dqd]

[PGP][PGP]

[coffee][coffee]

[discord]: https://discord.com/channels/@me/dqd#0143
[dqd]: https://github.com/dqdang
[PGP]: https://raw.githubusercontent.com/dqdang/dqdang.github.io/master/derek-dang.asc
[coffee]: https://www.buymeacoffee.com/dqdang
[abode]: https://github.com/dqdang/humble-abode
[updater]: https://github.com/dqdang/updater-tool
