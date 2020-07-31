---
title: Hosting Your Own Runescape Classic Private Server
layout: post
permalink: /hosting-runescape-classic-private-server
image: https://i.imgur.com/kedMcvr.png
---

Runescape was one of the first massively multiplayer video games in the world, reaching millions of users who built one of the largest communities to date, with active users to this day, and two successful sequels under its name.

But unfortunately, not everything lasts forever. The Runescape Classic team, the original version of the famous title still in use, will have to close its doors in the coming months for technical reasons. While it wasn't specified, it was likely due to being unable to resolve prominent glitches liek the unclosable Crystal Key chest.

The announcement, which was posted during the morning of May 23rd on their official site, indicates that the dilemma that has forced the closure of the title is its age. Runescape was released in 2001, making it one of the oldest multiplayer titles in the world.

The code, as well as the tools with which Runescape Classic was built, are simply no longer compatible or usable by the company, which also does not have access to all files due to the multiple restructurings that have taken place over the years.

However, thanks to independent developers, you can still host your own instance of Runescape classic on just about any server. And if you choose to expand the server to a large-scale audience, I would highly recommend using [managed cloud hosting services](http://www.temok.com/) from Temok, a managed hosting & It services provider.

## Which Server Software to Use?

In my [previous post](https://www.runescapehall.net/2020/04/27/runescape-classic-is-dead.html) on Runescpe Classic coming to an end, there are multiple software projects available to create a private server on your own VPS or cloud hosting. Considering you may want a more authentic experience, I think usig Open-RSC would be the best example.

The Open RSC project uses IntelliJ IDEA Community, OpenJDK 13+, and MariaDB (MySQL) server as the backbone of it’s code-base, so be sure to have those installed on your server, whether it’s Linux, BSD, or Windows based.

Clone the source code via:

> git clone https://github.com/Open-RSC/Core-Framework.git

change into the directory: 

> cd Core-Framework

And from there, you can go into the **server** folder and begin setting up your configuration file. Check out the official [Open RSC wiki](https://github.com/Open-RSC/Core-Framework#hosting) to learn how to get everything setup and launched properly.

It would be highly recommended to test this out on your own computer and to play in single player before launching a public server. Also, you should do your homework on how to secure a VPS or dedicated server to prevent break-ins if it happens to become popular.

## Will Official Servers Make a Comeback?

Runescape Classic had almost always been on shaky ground since RS2 was launched. It wasn't long before Jagex decided to make classic servers a members-only feature, and now it's completely switched off.

The employees familiar with classic's spaghetti code are long gone, and since the playerbase is quite small, it isn't profitable to re-launch this game. For the time being, it seems like recreations of Runescape Classic, hosted on on dedicated servers is the main way to go.
