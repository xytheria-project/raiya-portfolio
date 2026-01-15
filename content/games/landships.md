---
date: '2026-01-14T18:43:02-08:00'
draft: false
title: 'Project Landships'
weight: 5
---
_"A co-op multiplayer VR game in which two players control a tank as driver and gunner, and fight against other player-controlled tanks.  "_


{{< cards cols="2" >}}
  {{< card title="Role: Associate Developer" subtitle="Built for Oculus Rift (VR) with Unity, Photon Engine" >}}
  {{< youtube id="taQlqYHo0tM" >}}
{{< /cards >}}
											
For Project Landships, I tested out a variety of different networking options and tuned them. I would create different versions of the Unity project and mess around with settings, for example, changing which objects were tracked by the server or changing how they would communicate with the server, until we found something promising.

This was a multi-year long project run by a club in my university and had substantial work put into it before I joined. I joined for a semester and worked with four other people to make the existing VR tank battle game into a co-op multiplayer game.

There were many design challenges associated with this project: for example, the driver and gunner both pulled physics-based levers to control the tank. We had to decide if we wanted the state of the levers to be networked or if it would be local, and both options had drawbacks. A common issue was having the gunner and the driver de-sync and experience different states of the tank location at the same time. There was also the hassle of testing, as we had to use 2-3 computers and 2 people in order to run the multiplayer server and test two Oculus hosts controlling at the same time. 

The design challenges were honestly the largest of the issues with making the game multiplayer - once we had worked out the quirks, Photon Engine took care of the rest and handled most of the networking complexity. 
