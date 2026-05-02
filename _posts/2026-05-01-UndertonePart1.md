---
title: Undertone - pt. 1
date: 2026-05-01 20:36:00
categories: [Technology, Development]
tags: [undertone, rust]
description: A new idea for voice and community
---

# What Is an Undertone
According to the dictionary:

> undertone, n
> > A low or subdued utterance or accompanying sound
> > a quality (as of emotion) that is present but not clear or obvious
> > a subdued color
> > a secondary or underlying flavor or scent

What a flexible and evocative word, and one I resonate with when thinking about the potential and purpose of this project. Over the years I have had the pleasure of falling into some gaming communities that might best be described as niche. They take existing games and expand on the world through use of technology and what is fundamentally in all examples, role play. These communities come in many different shapes and forms:

- **Role Play** or purely the act of improvisation and collaborative storytelling through the framework of a video game.
- **Simulation** Whether pretending to be a pilot or race car driver, these communities focus on the skill sets and recreating the environment that these professions exist in, making the experience as real as possible.
- **Military Simulation** this one comes as a bit of a mix of the other two, allowing participants to take on roles and using tools, strategies, and procedures of military units.

## Origins
I have at one time or another participated in each of these, whether it was playing as a gunslinger in the old west on [*RedM*](https://redm.net)[^RedM], a news reporter in [*FiveM*](https://fivem.net)[^FiveM], or captain of military starship in *Star Citizen*[^SC]. In all cases not only was I enjoying the amazing gamed but experiencing them in ways never intended by the developers as part of a collaborative community intent on living in these universes together.

One thing that all of these communities have in common is a reliance on technology that is, due to their niche nature, not well supported. In almost all cases the communities use custom communication solutions to allow them to experience three-dimensional spatial audio and or realistic radio communications such as TeamSpeak 3 with custom plugins[^Plugins]. At the core is a need to enhance the experience and environment that the games do not natively support, or do not support sufficiently. Other solutions include narrow scope options like [Simple Radio Server] for [DCS] and [mumble] an older voice server that is open source, allowing integration and modification. On top of these tools communities typically also use products like [Discord](https://dicord.gg) as a communication platform for members and admin to provide support, communicate and stay in sync. Unfortunately these solutions are often flawed, cost money or have other hidden costs that these member supported communities must bare.

## Costs
Between the potential for data usage and exposure through Discord[^DiscordData] and the upfront cost to users to buy subscriptions, or "boost" communities to the costs of licensing products like TeamSpeak 3 or paying 3rd party hosts, paying for plugin subscriptions or buying necessary mods for games there is a very real burden placed on communities. Additionally, the communities often must pay for web hosting, server hosting and development costs associated with hosting and creating custom servers. A very small segment of servers are actually profitable businesses[^ForProfit] by charging for priority access to overcrowd or popular communities, or ones that offer very niche custom experiences behind closed doors.

Costs can also come in the form access: 

- **Disability Access**: In my experience very little consideration goes into meeting the needs of users with disabilities and can create impassable barriers to entry for some.
- **Financial Access**: The monetary costs to run communities and provide hardware and hosting is an obstacle that can discourage potential new communities from starting. While it is impossible to nullify all costs associated with operating a community it can be reduced.
- **Technology Access**: Whether through lack of expertise and experience in technology or computers, or lack of high end computers and fast internet connection, these barriers must be considered and mitigated where possible.

## OK Now What

With all this in mind, and I know it is a lot, I have begun the journey of research, experimentation and ideation to solve as many of these problems as I can. There is plenty I don't know, and even more I don't know I don't know, but I intend to do what I can and share that journey through this blog so that if nothing else, others might gain inspiration or learn from my mistakes.

If you would like to take part in the discussion or provide feed back please drop a comment here.

[^RedM]: RedM is a custom server and client for Rock Star Games [Red Dead Redemption II](https://www.rockstargames.com/reddeadredemption2)[^CFX]
[^FiveM]: FiveM is a custom server and client for Rock Star Games [Grand Theft Auto V](https://www.rockstargames.com/gta-v)[^CFX]
[^CFX]: [CFX](https://cfx.re) develops both FiveM and RedM on their CitizenFX framework, and were recently acquired by [Rock Star Games](https://www.rockstargames.com/)
[^SC]: Sci-fi sandbox game developed by [Robert's Space Industries](https://robertsspaceindustries.com/en/) helmed by Chris Roberts of Wing Commander fame.
[^Plugins]: Popular TeamSpeak 3 plugins include [Salty Chat](https://saltyhub.net/saltychat) and [Task Force Arma-3 Radio (TFAR)](https://github.com/michail-nikolaev/task-force-arma-3-radio)
[^DiscordData]: Discord officially states they will not sell user data, but it is also highly exposed to scraping by 3rd parties who may access and sell it as they please.
