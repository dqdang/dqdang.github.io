---
layout: post
title: digested clips
category: posts
---

*Subreddit scraper to create Youtube mirrors for Twitch clips.*

Twitch clips are common on reddit; capturing small snippets of a livestream and then posting to community subreddits gets some of the most attention of the day.

However, Twitch clips are always a pain to watch; they're slow to load (especially on mobile), buffer way too often, and scrubbing in any direction makes the previous two issues worse.

I can't seem to watch a 30 second video unless I wait upwards of 5 minutes while sipping my already cold coffee and eating my stale sandwich on my lunch break reading reddit.

So I decided I've had enough one day and created a bot to scrape a subreddit and comment YouTube mirrors for me. My specific instance is hosted on [this channel][channel].

I've written detailed instructions on how to get the bot up and running on the README for anyone that wants to host it.

Unfortunately, there's a bit of restriction with rate limiting for uploading videos to YouTube; and understandably so. The bot also needs a refresh token once in a while from Twitch. This makes the bot naive and dependent on maintenance.

Future alternatives include uploading to Streamable (API doesn't allow it currently) or playing a pure MP4 download from a natively hosted app. Any ideas, let me know.

Take a look at the project if you want:
[digested clips][digested clips]

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
[digested clips]: https://github.com/dqdang/digested-clips
[coffee]: https://www.buymeacoffee.com/dqdang
