---
layout: post
title: "Escape The Room"
author: Firas Cheaib
categories: experience
tags: [C++, Unreal Engine 4]
image: /img/escape-the-room.jpg
image_alt: Escape-The-Room
code: https://github.com/firsou/EscapeTheRoom
demo: https://mega.nz/#!14JBkDAQ!c3rlLSPRzUFTHyNGN0IR-CVahDgWedt-keFMEXKU67o

---

Escape The Room is my first Unreal Engine 4 project, developed as part of Ben Tristem's C++ Game Development course on Udemy.
It is a simple game, where the player must find a way to leave the room he finds himself in.

### Controls

	- W : Move Forward
	- A : Move Left
	- S : Move Backwards
	- D : Move Right
	- SPACE : Jump
	- Right Click : Grab Object
	
### Door Behavior

I used collision volumes and designed a C++ component "OpenDoor" to define door behavior.
The OpenDoor component defines and exposes a "PressurePlate" trigger volume. When the player hits the PressurePlate, the
door rotates.
Eventually, I converted the Door into a Blueprint Template and used keys on a float curve to animate the door.
I also recorded a door closing, and used this in the game.

