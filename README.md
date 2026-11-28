# Tally

Tally is a stream bot for Windows that runs your **Twitch and Kick** channels from one place. I'm a streamer who goes live on both platforms at the same time, and I got tired of juggling a different bot, a different alerts site and a different chat window for each one. So I started building the thing I actually wanted.

It's a desktop app. Your stuff lives on your PC, not on someone else's server.

> **This is a beta.** I use it on my own streams every day, but the look of the app and some features are still going to change. If something breaks, please tell me (see below).

## What it does

- **One chat for both platforms.** Twitch and Kick messages in a single window, with badges, emotes and who's around right now.
- **Commands** that work on Twitch and Kick at once, with cooldowns, permissions, variables and random replies.
- **Events and alerts.** Follows, subs, gifted subs, bits, Kicks, raids and a lot more. Build your alerts visually (video, sound, text, fonts) or write your own HTML, CSS and JS on top of the design.
- **Overlays for OBS.** Alerts, an on-screen chat you can style however you like, countdowns, clocks, rotating text, polls and predictions.
- **Effect queues**, so alerts don't step on each other. And if someone drops 200 bot follows on you, you can pause or clear the queue in one click.
- **Tally Deck.** Your own buttons to trigger things live, from the app or full screen on your phone (scan a QR code, same Wi-Fi).
- **Viewers and loyalty.** Watch time, messages, a channel currency, giveaways and quotes.
- **Stream info.** Change your title, category and tags on Twitch and Kick at the same time.
- **OBS control**, scheduled actions, moderation tools and Discord webhooks.
- **Imports** from Firebot and StreamElements, so you don't have to start from zero.

The app is in Spanish, English, Portuguese (Brazil) and Russian.

## Download

Grab the latest `Tally_x.y.z_x64-setup.exe` from the [Releases](../../releases/latest) page and run it.

Windows will probably show a blue "Windows protected your PC" screen the first time. That's because the installer isn't signed with a paid certificate. Click **More info → Run anyway**. You only see it once.

## Updates

Tally checks this page when it opens. When there's a new version you'll get a small bar at the top of the app with a button to update. It downloads, installs and opens again by itself. Every update is signed, so Tally will only install builds that come from me.

You can also check by hand in **Settings → Version**.

## Feedback and bugs

Open an [issue](../../issues) and tell me what happened, what you expected and, if you can, attach the log file. You'll find it in Settings → Advanced.

## About the code

This repo only holds the installers and release notes. The source code is private for now.
