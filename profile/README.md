# 🐟 Fish and Rips 🐧

We are a group dedicated to providing high quality, free software for making assets for Halo: Combat Evolved.

## Our projects

* **[🐧 Ringhopper](https://github.com/FishAndRips/ringhopper)**: This is our Halo: Combat Evolved asset development toolkit, consisting of the Ringhopper library and the Invader tool.
* **[🐁 zipmouse](https://github.com/FishAndRips/zipmouse)**: This is a Rust-based library for making Zstandard-compressed zip files. We use this in Ringhopper, but it can be used externally.

## Our cardinal rule: no secret clubs

What sets us apart from most other groups is that all of the above projects are done out in the open. You definitely can't say the same about most Halo modding projects, where projects tend to be locked behind secret, exclusive Discord channels and private repositories (we call these "secret clubs").

In fact, much of Halo's history has been plagued with secret clubs, even going as far back as its initial release on PC in 2003, where secret forums of only the elite few had access to the "good stuff" as far as modding goes. Not only that, but maps created by these people would often be obfuscated ("protected"), preventing other people from learning from the tags as well as preventing the community from maintaining the maps when their authors would inevitably leave the community.

Thankfully, after many years, secret clubs and map protection *mostly* died off as interest in the game fell, with only a very small handful of actively developed things still being kept behind closed doors near the end of the 2010's (mostly mods). However, once MCC and CEA were released, interest increased, and so too did the number of secret clubs.

We want to do away with secret clubs, because it is antithetical to the spirit of modding, and it only causes harm in the long run.
* We aren't going to dangle screenshots and videos in front of you to hype up something that won't be released for a long time.
* We aren't going to keep builds only to a small group of people while everyone else has to wait.
* We're not going to delay releasing things for many months or years for a "surprise" factor.
* *All* releases are backed by source code.

## Accuracy and good diagnostics

In order for tools to be good, they need to be accurate and provide good feedback to the user.

We prioritize keeping things as accurate as possible. Tag extraction needs to create tags that resemble the original tags as closely as possible. This is to minimize bugs while providing the cleanest tags you can get. Additionally, certain quirks, such as Halo's really bad sprite processing, must be kept in place, simply because some tags cannot be made without it.

Additionally, we need to provide good feedback to the user. For example, when an error occurs on official tools, you are generally left with either cryptic assertions or useless register dumps. Our tools will actually tell you what's wrong, and you may even have an automated way to fix the problem.

## Everything is free software

When it comes to projects, there is generally no such thing as people who "eventually release the source". Basically, most things that start closed source stay closed source, and we won't kid ourselves into thinking the opposite is true. Sure, it does happen once or twice out of dozens, but that is the exception, not the rule.

This is why we use the GPL software license for our code. This guarantees that all binary and source distributions remain free, from start to finish, with corresponding source code never being kept from users. And this rule applies no matter what generation user they may be, whether it is us, you, your users, their users, and so on.

## You don't need GitHub to contribute

What's that? You *don't* want to give GitHub your data? Wow, you're in luck!

Did you know that Git and the concept of pull requests predate GitHub? That's right! You actually *don't* need a GitHub account to contribute.

Simply shoot us an e-mail with your patch (you can use `git format-patch`) or, if you have a public-facing Git instance hosting your changes, a link to your repo and the name of the branch. Like GitHub pull requests, if changes are needed or if we decline your pull request, we'll let you know. Otherwise, if everything is good, it'll be committed.
