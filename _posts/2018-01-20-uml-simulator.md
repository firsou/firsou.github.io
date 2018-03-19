---
layout: post
title: "SimulatorJS"
author: Firas Cheaib
categories: experience
tags: [Javascript, node.js, jQuery, socket.io, express, bootstrap]
image: /img/UML-simulator.png
image_alt: SimulatorJS
code: https://github.com/firsou/SimulatorJS
demo: http://gunray.skip.chalmers.se:3000
---

SimulatorJS is a distributed UML Diagram Simulator developed as part of a research project at 
the University of Gothenburg/Chalmers University.

### Main Features

	- Upload your diagrams using JSON Files
	- Play animations simultaneously on several devices
	- Chat Room
	
### Diagrams

It is capable of simulating and distributing three types of UML Diagrams:

	- System Sequence Diagrams (SSD)
	- Class Diagrams
	- Deployment Diagrams
	
### Distribution

The first client connected to the server will be the Submitter and will be able to submit 3 JSON Files at most.
Subsequent clients will be viewers and will directly see the output page.
The Simulator distributes an x amount of processes of the diagram across an n amount of nodes.
If there are n nodes connected to the system, each node will handle x / n amount of processes.
The processes handled by the current client are emphasized in a darker color.
Furthermore, the animation will play at the same time when initiated by the submitter, across all clients and devices.
The frontend is mobile friendly and can be used on several handheld devices.



