---
layout: project
title: 'Sniper Elite 4 Apple'
date: '08-01-2025'
sitemap: false
image: /assets/portfolio/rebellion/se4_apple/se4_apple.gif
---
Sniper Elite 4 for Apple was my first job in the games industry.

The project initially began with just myself and one other junior programmer.
Within a few months, we had the game running and rendering on Apple hardware.
Once the project reached a stable point, two senior developers joined and the project went into full production.

Apple’s ecosystem took some time to get acquainted with, even though there are many practices that transfer across from Windows.
When working with Objective-C (ObjC) something you inevitably encounter when dealing with Metal or NSObjects is the strange way object ownership works.
It was unusual at first, but you become accustom to it. Core concepts like memory management and multithreading follow these own rules when using Cocoa and ObjC
[find out more here.](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/MemoryMgmt/Articles/mmRules.html#//apple_ref/doc/uid/20000994-SW1).

I leveraged my low level graphics expertise from working with Vulkan and DirectX while implementing Metal as a supported graphics API for the Asura engine.
This work ranged from updating the engine’s export pipeline to support iOS builds alongside adding Jenkins integration, to developing bespoke memory management systems for Metal resources on both iOS and macOS.
This formed the bulk of the work and accounted for most of the development time.

Alongside these responsibilities, I also implemented several key Apple ecosystem features, including On Demand Resources (ODR), In App Purchases (IAP) and Lifetime Management
Many of these systems were outdated at the time and not built with games of Sniper Elite’s scale in mind, so getting them to behave reliably required significant effort.
Since then, Apple has taken our feedback into account and released a new system Managed Background Assets (MBA) which addresses many of the issues we encountered.

As a small team, collaboration was essential. I worked closely with fellow programmers, artists, and QA to help deliver Sniper Elite 4 on Apple platforms in January 2025, where it was met with a great reception.

Following the January release, we delivered several improvements and fixes, including a 60fps mode, tessellation support for M4-class devices and above, and full keyboard and mouse support.

<iframe width="100%" height=500 src="https://www.youtube.com/embed/3y1M2u2OQrQ?si=VpJMo_oIOAi2V3Q-" frameborder="0" allowfullscreen></iframe>