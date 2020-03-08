---
layout: post
title: "Reclaim your privacy"
description: "Some tips to block unwanted content and trackers online"
date: 2020-03-08
tags: [privacy, ads, tracking]
comments: false
share: true
---

Reclaim your privacy

Once every few days, I find myself listening to somebody squeal ***"Instagram is listening to our converstions"*** and pointing fingers at a well targeted ad. My short response is usually something like- ***"Its 2020, duh!"*** or ***"I'm sorry but Privacy isn't cheap"***

For those inquisitive folks, I do have a longer response. But, off late, I'm starting to get tired of  revisiting the exact same conversation. I've decided to write this post up to save my time and send all the squealers here.  As you might already know, the entire online advertising industry thrives on monetizing private user information and if you haven't explicitly turned off Ad Tracking on your phone or browser, you are essentially letting apps and websites profile your browsing activity. As you start using more apps and websites, you start giving away more information which naturally makes your persona richer for websites and apps to target ads.

To go back to where we started- Instagram isn't listening to our conversations. The reason why ad targeting is mostly accurate is because, one or more members participating in a conversation usually end up searching for the subject or topic which ends up being tracked by Instagram. Now that instagram has this information along with everybody's location data, it only makes sense for Instagram to stitch this information together and target every person who shared the same location history. Also, humans are predictable which makes Instagram run thousands of experiments to make Ad Tracking accurate.

How do you maintain a certain degree of privacy? How do you prevent Ad Tracking?

Here are some tips which might help you stay safe and private while you browse the internet.

1. Disable Ad Tracking (***Setup time: <1 min | Difficulty: Easy***)

    On Android, go to `Settings > Privacy > Advanced > Ads` and toggle on Opt out of `Ads Personalization` .

    On iOS, navigate to `Settings > Privacy > Advertising` and toggle on `Limit Ad Tracking`.

    Make sure that you also reset your Advertising Identifer. All your browsing activity from this point will be profiled under a new identity. So, the ads that you might start seeing might not be relavant anymore.

2. Use a privacy focussed Browser (***Setup time: <15 min | Difficulty: Intermediate***)

    - [Brave](https://brave.com/) is a privacy focussed browser which blocks ads and trackers out of the box. It is built on top of chromium, so your favourite browser extensions work on Brave as well.
    - [Firefox](https://www.mozilla.org/en-US/firefox/new/)  has built-in tracking protection and does a pretty good job at blocking trackers.

    If you are currently using Chrome, switching to Brave or Firefox shouldn't be hard. All your bookmarks, extensions and browser history can be imported easily. I would highly recommend switching to Brave/Firefox. However, if you do not wish to change your browser, you can install the following browser extensions:

    - [Ghostery](https://www.ghostery.com/) lets you block unwanted traffic and prevent trackers.
    - [Ad Block Plus](https://adblockplus.org/) blocks ads on websites.
    - [DuckDuckGo](https://duckduckgo.com/) is a privacy focussed search engine.

3. Use a Hostfile or Network Monitor (***Setup time: <5 min | Difficulty: Hard***)

    - A hostfile would prevent your computer from connecting to specific internet hosts and is proven to be an effective way to block trackers.[Instructions](https://someonewhocares.org/hosts/)

    - [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) lets you monitor your Mac's realtime network traffic and add rules to allow/deny any connection.

4. Use a DNS level blocker (***Setup time: ~30 min | Difficulty: Hard***)

    [Pi-hole](https://pi-hole.net/) is a DNS sink hole that protects you from unwanted content and trackers. You can set this up on a RasberryPi by following [this guide](https://www.smarthomebeginner.com/pi-hole-setup-guide/).

    I would highly recommend setting up a hardware DNS level Ad blocker, but if you'd like something similar to PiHole without having to go through all the hassle of setting up a Rasberry Pi, you can checkout a VPN service like [NextDNS](https://nextdns.io/) or [Cloudflare Warp](https://blog.cloudflare.com/1111-warp-better-vpn/). They typically offer the same DNS level protection from trackers.