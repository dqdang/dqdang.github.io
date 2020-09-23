---
layout: post
title: environment
category: posts
---

Unfortunately for tree huggers, this isn't one of those posts.

I have a couple scripts to recreate a development enviroment I'm comfortable with.

Dev environment are always a huge hassle when migrating from computer to computer, so keeping organized alleviates the onboarding process.

As the saying goes: if I had 3 hours to chop a tree, I spend 2 hours sharpening my axe.

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

This is what my directory tree of my Unix environment looks like:
/Users/Administrator/Downloads
```
Users
└───$User
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

These are the scripts to get me going: [abode][abode]

Here's a script that takes the python directories in the git folder and installs their requirements: [updater][updater]

---

[messenger][facebook]

[github][dqd]

[reddit][reddit]

[PGP][PGP]

[coffee][coffee]

[facebook]: https://www.m.me/dqdang1
[dqd]: https://github.com/dqdang
[reddit]: https://www.reddit.com/user/outsidefarmland/
[PGP]: https://raw.githubusercontent.com/dqdang/dqdang.github.io/master/derek-dang.asc
[channel]: https://www.youtube.com/channel/UCfZ5RkmbZACUciI1IDncxJQ/
[updater]: https://github.com/dqdang/updater-tool
[abode]: https://github.com/dqdang/humble-abode
[coffee]: https://www.buymeacoffee.com/dqdang