---
layout: post
title: dev environment
category: posts
---

*Set of environment scripts for future reference*

Unfortunately for tree huggers, this isn't one of those posts. Sorry.

I have a couple scripts to recreate a development enviroment I'm comfortable with.

Dev environment are always a huge hassle when migrating from computer to computer, so keeping organized alleviates the onboarding process.

As the saying goes: if I had 3 hours to chop a tree, I would spend 2 hours sharpening my axe. Sorry again tree huggers.
<br/>

This is what my directory tree of my Windows environment looks like:
```
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
```
<br/>

This is what my directory tree of my Mac environment looks like:
```
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
```
<br/>

This is what my directory tree of my Unix environment looks like:
```
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
```
<br/>

These are the scripts to get things going: [abode][abode]

Here's a script that takes the python directories in the git folder and installs their requirements: [updater][updater]

---

[messenger][facebook]

[github][dqd]

[PGP][PGP]

[coffee][coffee]

[facebook]: https://www.m.me/dqdang1
[dqd]: https://github.com/dqdang
[PGP]: https://raw.githubusercontent.com/dqdang/dqdang.github.io/master/derek-dang.asc
[coffee]: https://www.buymeacoffee.com/dqdang
[abode]: https://github.com/dqdang/humble-abode
[updater]: https://github.com/dqdang/updater-tool
