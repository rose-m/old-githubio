+++
date = "2017-06-18T16:59:48+02:00"
description = "Getting work done in the zone with the help of Alfred"
title = "Focus with Alfred"
+++

One of things that kept bugging me at work was a problem a lot of may be familiar with: switching contexts far too often. Colleagues come and ask questions, mails arrive, notifications pop up -- a typical workday for me is often interrupted by various things, some more, some less important.

Of course, this immediately kills productivity and concentration especially as a developer -- there's the one image describing it at its core:

![Developer focus after an interruption][devProd]

As a result of this I was hardly able to really progress in my tasks and needed to turn this over again.

## Keeping Focus
The approach I took was to take myself certain time blocks, typically either 30 or 45 minutes. Then I'd go along and do the following:

* disable notifications in macOS
* start a timer to keep track when time is up
* enable flight mode on my mobile
* ... and finally set `/dnd` mode in Slack and set my `/status` to indicate to my co-workers that I really don't want to be interrupted

It turned out to be quite successful -- I could definitely get more work done again but one thing was still odd: I was clicking a lot to enable and disable everything. What do you do as a lazy developer? Yes -- you automate.

## Alfred to the Rescue
Some of you may already be familiar with [Alfred App][alfred] -- the handy and powerful brother of _Spotlight_. I have been using it for quite a while now so the decision was easy to create my own workflow for Alfred.

So, that is what happened and here's how it looks:

![Starting Focus Mode](./focus_start.gif)

Using `focus 20` I can now start my _focus time_ of 20 minutes, automatically have notifications disabled, _Slack_ status set, and all reverted after the time is up. While it is active I can of course stop it manually by using `focus` again or just see the remaining time:

![Stopping Focus Mode](./focus_stop.gif)

I published this one alongside with another one to easily create screen captures and store them as GIFs -- as used in this post.

Check them out here: [https://github.com/rose-m/alflows](https://github.com/rose-m/alflows) and let me know what you think!

[devProd]: https://i.stack.imgur.com/oYpue.png
[alfred]: https://alfredapp.com