---
title: Electronic Heijunka Board
excerpt: >-
  A Heijunka Board is a visual scheduling tool used to achieve smooth production
  flow. Here, we automate the manual Heijunka setup from existing demand and
  implement a few different production scheduling algorithms.
date: '2021-05-27'
thumb_img_path: /images/Math.png
thumb_img_alt: Icelandic horses
content_img_alt: Icelandic horses
layout: post
---
A Heijunka box is a visual scheduling tool used in Heijunka, a concept originally created by Toyota in their TPS system to achieve smoother production flow. Typically, a n b m box is created with products on the n axis and time on the m axis.

![](/images/Heijunka%20Box.PNG)

To facilitate just in time production, a process should only produce goods as they need them and a manual system of cards ensures that operators work evenly to match optimal tempo of goods needed for the day. This is typically determined by looking at demand needed within three days.

Of course, in any good decision support system, The operator possesses domain knowledge that is vital to the smoothing functioning of the system. An operator knows the kinks, tricks, and limitations in optimal short term schedules.

Yet, repetitive tasks get in the way of unleashing this creativity. A time study reveals that the mechanics of operating the board takes up just as much time as the scheduling decision making.

![](/images/Setup.PNG)

Our poor operator wakes up a 5 am everyday to pull from archaic ERP systems, lays out the cards, and runs excel calculations to create the final recommendation. If we look at this process, there are so many manual steps where mistakes can occur and cause supply chain whiplash downstream in the system.

![](/images/Manual%20Process.PNG)

Why not automate this entire process with decision support, improve algorithms, and better visual displays, and have the system print out the production stickers in one go? We'll hook up ERP to python code, create an editable excel front-end, and stick the VBA buttons to the SQL server that prints the final sticker barcodes to start the production of product.

![](/images/Electronic%20Heijunka%20Board.png)

This result is the simplified process below. Much less steps!

![](/images/Faster.PNG)

It is much faster as well! Not only are there time savings in operation that can spare floor capacity to other issues, the production schedule is better optimized to match the demand. There's also less mistakes in this entire process!

![](/images/Stats.PNG)

To read the full whitepaper, click [here](https://github.com/IamJasonBian/IamJasonBian/files/6504722/Heijunka.Whitepaper.pdf).
