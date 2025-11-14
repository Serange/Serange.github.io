---
layout: project
title: WaterNav
date: '01-06-2023'
#accent_image: /assets/portfolio/waternav/accent_image_1.png
image: 
    path: /assets/portfolio/waternav/WaterNav.png
links:
  - title: Link
    url: https://www.rivercanalrescue.co.uk/index.php/waternav-app/
caption: Ditch the map its on the app.
---

WaterNav is a free app for iOS and Android devices used for canal boat navigation. It was originally developed for Android before I arrived and was exclusive to that platform.

During my university placement year in 2020, I worked with River Canal Rescue (RCR) to port their existing Android app over to iOS.
During this time, I also overhauled the Android app to give it a more modern look and feel.
I rewrote most of the Java code as part of this overhaul, along with resolving legacy issues with Google Play.

After gaining an in-depth understanding of the Android version, I started work on the iOS version at the beginning of 2021.
The goal was to match the features we had on Android with a native and performant implementation on iOS.

Considerations were made for taking a cross platform approach by having a single project that would deploy both versions.
However, due to WaterNav's UI heavy nature and lack of forethought for multiplatform support in the original Android app, we decided to build the iOS version from scratch.
After around six months, iOS was at full feature parity with a few additional quality of life improvements.

![](/assets/portfolio/waternav/poi.png)

Around this time, the COVID pandemic happened.
I decided to take a gap year from university to allow things to settle whilst also aiming to further my professional experience.
I took a permanent job that would continue through to and beyond my final year of university.

From this point onward, development pivoted toward dual support for both iOS and Android.
WaterNav became its own internal department, and I stepped into a lead programming role.

- Rewriting the database to support offline route planning and reduce the download size.

We hired another developer to focus on Android, whilst I continued iOS development.
Feature development became a coordinated effort across both platforms.

Some key features I developed were:

:-:|:-:|:-:
Offline Route Planning | Online Live Data | RCR Membership Integration
![](/assets/portfolio/waternav/routeplanning.png) | ![](/assets/portfolio/waternav/updatelivedata.png) | ![](/assets/portfolio/waternav/rcrintegration.png)

Offline Route Planning: Allowed users to plan routes along the canals without needing a signal.
Built using A* pathfinding on a proprietary dataset, with customisable routing settings to suit individual preferences.

Online Live Data: Worked similar to Waze. This let users update key locations (e.g. marinas and moorings) and flag hazards in real time.

RCR Membership Integration: Enabled users to access and manage their RCR membership directly within the app. 
Along with the user being able to manage their membership; it was integrated into the engineers system
so engineers could manage stock and jobs directly from the app without the need to call the office. 
It effectively became a one stop shop for all the users needs.

Alongside development I also helped establish WaterNav’s presence as a product and brand
Attending trade shows to reach our demographic and demonstrate the advantages of WaterNav over competitors and traditional paper maps,
with a few live walkthroughs throughout the day.

Alongside development, I also helped establish WaterNav’s presence as a product and brand.
As a team, we attended trade shows to reach our demographic and demonstrate the advantages of WaterNav over competitors and traditional paper maps.
Attending the trade shows allowed live walk through to take place throughout the day.

![](/assets/portfolio/waternav/tradeshow.png)

I moved on from RCR and WaterNav in June of 2023, after nearly three years with the team.
It was a great chapter of my life I look back on fondly.
I learnt a lot, found my leadership legs and worked alongside some amazing people.
Stepping away wasn’t an easy decision; however, it felt like the right time to explore new opportunities and continue developing my skills.