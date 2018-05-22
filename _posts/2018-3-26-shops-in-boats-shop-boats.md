---
layout: post
title: Shops... In Boats... Shop Boats!
---

Hello! Today I've came up with an idea because I want to make the game a bit more interesting and also add a purpose to earning gold. The idea I came up with is shop boats. These are boats where your tugboat is able to pull up alongside and buy powerups and other items with the gold you collected. Since I'm using the Phaser game framework (I highly recommend it by the way, you can find it here), I've been messing around with faking the illusion of how all the boats move when your boat stops, because it doesn't make a ton of sense for boats to come at you while buying items next to a shop boat. 

Since I want to keep input for the player as easy as possible, I'm trying to ensure everything can be controlled with a single touch or mouse click, with no other keyboard keys or anything else. Because of this, the way that I implemented interfacing with a shop boat is you move within range of a shop boat and an exclamation mark will appear above your tugboat. All you need to do next to interact with the shop boat is click anywhere on the game screen and the GUI (graphical user interface) will appear allowing you to buy powerups and items. 

While trying to implement the shop boat interface, it has been challenging triggering events when the interface is opened and closed. For example, as of the time I'm writing this post, the invisible shop boat GUI is stuck open preventing the player from being able to move, even though there's no obvious reason that it shouldn't close since I'm using a simple boolean condition. It shouldn't be too hard of a bug to solve, just a slightly tricky one. I should be able to iron that out tonight and hopefully get the shop boat interface working. 

Today has been quite productive so far, since I've been able to work on it for two hours during school it gave me a head start on creating the basis of the shop boat interface. It will be super exciting once I finish the interface and I can't wait to share a teaser of how it works when it's complete!