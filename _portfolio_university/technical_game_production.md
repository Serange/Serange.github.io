---
layout: project
title: 'Technical Game Production'
date: '12-06-2020'
description: >
    Dabbling with Unreal Engine
sitemap: false
image: 
    path: /assets/portfolio/university/tgp/tgp.gif
---

TGP or Technical Game Production was a group project where myself and 4 other programmers,
from the same course, were tasked with building a game with Unreal Engine 4 over a 6 week period.

As a team we decided to go for a roguelike puzzle arcade game, simple aim of the game was the get the highest score and you had the 1 run to do it.
We opted to have the map procedurally generation based on a selection of room templates that would design. 

I was primarily in charge of the map generation along with integration of room designs and the ability to allow gameplay elements tied to the room templates
like puzzles to externally affect the world elements mainly so that you would get locked into puzzle rooms until you could solve it then when complete the gates
would open which were controlled by the map generator.

My primary responsibility was the procedural map generation, including the integration of room templates and enabling the gameplay elements within them to externally interact with the map generator.
For example, puzzle rooms would lock the player in until the puzzle was solved. Once completed, the gates would open. 
The puzzle elements needed a way to communicate with something it was unaware of to solve this we opted to use delegates and bind the puzzle objects to the room it was spawned in allowing communication

It was really fun in the short amount of time that we had. 

<iframe width="100%" height=500 src="http://www.youtube.com/embed/JzPBCHLgQPM" frameborder="0" allowfullscreen></iframe>
