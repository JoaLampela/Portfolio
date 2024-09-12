---
title: "Hot Hands Furnace"
categories:
  - Top Projects
---

Hot Hands Furnace is a card game with a twist: instead of taking turns, both players play cards simultaneously in real time.

![Hot Hands Furnace]({{site.url}}{{site.baseurl}}/assets/images/hot-hands.png)

This game was Team Brute Force's entry for the fourth task of University Gamedev League 2022, which was a game development competition hosted by [Nine66][nine66], a member of the [Savvy Games Group][savvy-games-group]. For this task, teams had to make a card game that could support NFTs.

Many of the team members had worked together on a game concept for a real-time card game, so we decided to move forward with that idea. Card effects were kept simple and understandable while introducing interaction using a countdown-based spell system. The game's speed was also made to increase as players' hands warmed up during the course of a match. The game ended up winning this round of the competition.

I was responsible for the game's netcode and the AWS services' implementation in the cloud.

The game features 60+ unique cards with persistent player profiles with fully customizable decks that are stored in the cloud.

![Deck Builder]({{site.url}}{{site.baseurl}}/assets/images/hh-deck-builder.png)
Card collection and deck builder.

The game also contains a global chat with persistent history in the main menu for talking to other players. The chat messages persist for a few hours before they're no longer being displayed.

![Chat]({{site.url}}{{site.baseurl}}/assets/images/hh-chat.png)
Global chat.

I was responsible for the AWS services' implementation in the cloud as well as the netcode in the game. Users' accounts and their collections were stored in the cloud. The netcode for the game used Unity's Netcode for GameObjects to handle gameplay commands. As the Team Lead, I was also responsible for general project management and planning.

The game was made in under a month using Unity and Amazon Web Services.

You can check out Hot Hands Furnace's [itch.io page][website] for more information and a downloadable zip file of the game.

[nine66]: https://www.linkedin.com/company/nine66/
[savvy-games-group]: https://savvygames.com/
[website]: https://hunnydragon.itch.io/hothandsfurnace
