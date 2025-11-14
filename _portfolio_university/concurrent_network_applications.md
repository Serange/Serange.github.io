---
layout: project
title: 'Concurrent Network Applications'
date: '20-12-2019'
description: >
    Multiplayer 101
sitemap: false
image: 
    path: /assets/portfolio/university/cna/cna.gif
---

This project was about creating a desktop application where you could connect with other users within the same application across the network.
It was made in C# various systems were made such as a live chat system along with commands to start games like Rock Paper Scissors and Checkers.

## Text Chat
![Users setting up their nicknames and chatting](/assets/portfolio/university/cna/cna_window_client1.png)
![Users setting up their nicknames and chatting](/assets/portfolio/university/cna/cna_window_client2.png)
*Users setting up their nicknames and chatting*

It was my first endeavour into dealing with live networking systems along with C# as a language. 
Implementation of both the TCP and UDP protocol were implemented depending on use case. 
Primarily the text system was using TCP whereas when playing Checkers it would opt to use UDP as is the norm for most online games.

## Rock Paper Scissors
![Users setting up a game of Rock Paper Scissors via private game invites](/assets/portfolio/university/cna/cna_window_client1_rps.png)
![Users setting up a game of Rock Paper Scissors via private game invites](/assets/portfolio/university/cna/cna_window_client2_rps.png)
*Users setting up a game of Rock Paper Scissors via private game invites*

![Users playing a game of Rock Paper Scissors](/assets/portfolio/university/cna/cna_window_rps_ingame.png)
![Users playing a game of Rock Paper Scissors](/assets/portfolio/university/cna/cna_window_rps_ingame_selected.png)
![Users playing a game of Rock Paper Scissors](/assets/portfolio/university/cna/cna_window_rps_ingame_finished.png)
*Users playing a game of Rock Paper Scissors*

## Checkers

Playing Checkers wasn't the most intuitive i'd have prefered a drag and drop mechanic but keybinds were the simplest to implement to demonstrate a live network application.
Controlling the checkers requires using A, D, Z, and C: A for up-left, D for up-right, Z for down-left, and C for down-right.. 

![Users playing a games of Checkers via private game invites](/assets/portfolio/university/cna/cna_window_client1_checkers.png)
![Users playing a games of Checkers via private game invites](/assets/portfolio/university/cna/cna_window_client2_checkers.png)
*Users playing a games of Checkers via private game invites*

Looking back I'd have improved the controls so you could do drag and drop.
Along with stating in the text chat whose turn it was along with their associated colour.