---
layout: post
title: Porting from Phaser 2 to Phaser 3!
---

Hello everyone! The last few days I have been working on transitioning my game over to Phaser 3. While the preview may not look like much, I created some basic and boring placeholder sprites so I can nail down the main mechanics as best I can. Through the use of placeholder graphics, I think I have been able to accelerate the development time of the port and still be able to release on time within a few weeks.

One thing I'm not so sure about is the iOS and Android release, I have been trying to get the Crosswalk plugin to work with NodeJS, but have had issues creating the project. In theory, with the use of the Crosswalk plugin I would be able configure my game to use a WebGL accelerated browser vs the default browser which makes the game very laggy on mobile devices. I haven't looked into the issues with this too much since I've been trying to grasp Phaser 3.

Not much else has been going on, the port is coming along smoothly. Probably my favorite feature of Phaser 3 so far is the easy sprite layering. I can simply call sprite.setDepth to order my sprites nicely. What an improvement since Phaser 2, whew!

I hope everyone is having a great week! I will post another update in a couple days.