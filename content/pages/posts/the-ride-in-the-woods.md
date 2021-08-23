---
title: Van Life Desk Setup for Tech Work
date: '2020-04-23'
thumb_img_path: /images/Van_Life.png
thumb_img_alt: null
content_img_alt: A motorcycle in a forest
seo:
  title: The Ride In The Woods
  description: A cautionary tale about riding
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: The Ride In The Woods
      keyName: property
    - name: 'og:description'
      value: A cautionary tale about riding
      keyName: property
    - name: 'og:image'
      value: images/3.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: The Ride In The Woods
    - name: 'twitter:description'
      value: A cautionary tale about riding
    - name: 'twitter:image'
      value: images/3.jpg
      relativeUrl: true
layout: post
excerpt: >-
  With soaring real-estate prices, friends in different cities, and the promise
  of a minimalistic life free of modern trappings, I have been building a
  van-house within my Ford Transit 250 high roof. To enable a sustainable career
  in the van, I need to ensure good technological capacity to grow and compete
  globally.
---
With soaring real-estate prices, friends in different cities, and the promise of a minimalistic life free of modern trappings, I have been building a van-house within my Ford Transit 250 high roof van.

![](/images/Van_Life-a5825bd9.png)

Some people build their vans for mountain biking, some people build their vans to surf. For me, I wanted a van where it is easy to get work done inside. This requires good technological capacity to grow in and compete globally as a tech worker.

Internet connectivity is the lifeblood of our trade. With the advent of several emerging technologies such as Starlink and impeding 5G rollout, we are nearing the possibilities of consumer grade edge computing, lidar systems, and simple internet of things applications. For me, I'm focused on just getting the best coverage and speeds that can be offered to a guy in a van.

To do quality work in a housevan, we want internet that is of comparable quality as a workstation in the office. This allows us to keep up competitively  in the remote work landscape. We'll need powerful computers, sufficient battery capacity, duo monitors, and reliable wifi setup with sufficient speeds and coverage. By being able to match any office worker in meeting presence, screen-sharing, multi-tasking, and instantaneous analysis, we gain the ability for others to feel our presence in the office.

To fuel this vision, I broke my van setup into the following sections

1.  Powerful Computing

2.  Sufficient Battery Capacity

3.  Duo Monitor Workstation

4.  Reliable Wifi Setup

**Powerful Computing:**

To power computation inside  the Van, I will use a custom built GPU intensive computer. Components Inside include:

*   GeForce RTX 2080 Super

*   Gigabyte X570 AORUS Master Motherboard

*   Corsair silver RM 850x power supply

*   Corsair Hydro Series H100x liquid cooling

*   Intel i7 Core



![](/images/Comp-e12309e2.jpg)



With the above components, we’re looking at averaging 3.8 kWh per day on a 8 hour workday + 3 hour idle surfing when looking at average power consumption over 30 days. Having a powerful computer here allows us to screen-share for work, run analytics software which consume a lot of memory at high speed locally (Think Power Bi), and juggle many tabs excels files open at once as an analyst.

**Sufficient Battery Capacity:**

In addition to the 3.8 kWh needed for the workstation, other appliances include desktop monitors, a fridge, hot water heaters, a microwave, and a stove. In total we provision two LifePo4 BigBatteries for 8.6 kWh of capacity.

![](/images/Battery%20Power.PNG)

To power this setup, solar is used with a max charge of 70A at 24V. This allows our batteries to charge in max sunlight over 5.1 hours.(8.6 kWh/(70A\*24V). In more temperate climates with lower solar efficiency however, the entire capacity might take up to 8 to 9 hours to charge. We also hold shore power and a diesel generator onboard to help us maintain sufficient power.

![](/images/Solar%20Mount.PNG)

To reduce our battery consumption, we can play with overclocking/cooling within the main PC, opt for more efficient monitors, switch to AMD from Intel on the processor side, and reduce consumption using built in windows power management programs. This will allow us to cook more and shower more (can’t spend all of our time in van overworked!).

**Duo Monitors:**

Duo monitors are a must for true quants. From wall street traders to our local SWE I in FANNG, there’s never a downside in having more monitors. We create duo monitors mounts as shown below to enable a similar workstation as seen in the office.

*   To support the duo monitors, we create an island in the middle to pull the monitors over and place the gaming pc underneath via wooden supports.

*   Our monitors draw 0.8 kWh on a 8 hour workday + 3 hour idle averaged over 30 days, but there is possibility to improve this via more energy efficient monitors. Luckily we provisioned enough battery capability!

![](/images/Duo%20Monitor.PNG)

*   To support the duo monitors, we create an island in the middle to pull the monitors over and place the gaming pc underneath via wooden supports.

<!---->

*   Our monitors draw 0.8 kWh on a 8 hour workday + 3 hour idle averaged over 30 days, but there is possibility to improve this via more energy efficient monitors. Luckily we provisioned enough battery capability!

**Reliable Wifi Setup:**

After some research, the main tradeoffs I see are:

Starlink vs Existing Carriers, 4G vs 5G, and hotspot selection.

Starlink vs Existing Carriers:

As of today (5.25.2021), Starlink is available to a limited number of users per coverage area. This means that users are limited to their zip code and moving requires setting up a new zip code. Typical lead-times for Starlink devices can take between 3 to 6 months and there are plans for the service becoming fully mobile by the end of 2021.

Currently the Starlink plan composes of the following rings of satellites:

*   First shell: 1,440 in a 550 km (340 mi) 

    [a](https://en.wikipedia.org/wiki/Orbital_altitude)

    ltitude shell at 53.0° inclination

*   Second shell: 1,440 in a 540 km (340 mi) shell at 53.2° inclination

*   Third shell: 720 in a 570 km (350 mi) shell at 70° inclination

*   Fourth shell: 336 in a 560 km (350 mi) shell at 97.6°

*   Fifth shell: 172 satellites in a 560 km (350 mi) shell at 97.6°

1677 satellites have been launched so far with the service in beta. Beta tests from users show consistently high downloads speeds from 57 to 155 Mbps and 6 to 10 Mbps upload speeds, but uptime leaves much to be desired. Typically, user reported uptimes are from 83 to 88% on 2 hour test. Figure one shows the typical uptime pattern.

![](/images/Upload%20Pattern.PNG)

Given the long lead-times on Starlink, the constant launching of more satellites, and the promise of fully mobile untethering. Starlink looks like a risky long term investment with the potential to provide universally good coverage in rural areas. As shown below, Starlink speeds are consistent nationwide for it’s top coverage counties while carriers can vary wildly for it’s top counties.

![](/images/Star_Link%2030%20best.PNG)

I reserved a pre-order to see the state of the technology this fall.

Next, we fallback to the tried and true 4G/5G network technology. The figure below shows the promises of 4G vs 5G.

![](/images/4G%20vs%205G.PNG)

In the 4G world, the Jetpack 8800L ($199) from Verizon and Nighthawk MR1100 LTE Mobile Hotspot from AT\&T ($250) currently lead the pack. T-Mobile also offers the Franklin T9 Mobile Hotpot ($89.99).

Jetpack 8800L and Nighthawk reportedly offers up to 100 Mps within 4G networks while T-Mobile offers a cheaper data-plan but lower max speeds as well.

Within 5G, Inseego MiFi M2100 5G UW ($399.99) and Nighthawk 5G Mobile Hotspot Pro ($509.99) stand out as being 4G compatible and 5G ready. Currently major carriers have the following 5G coverage statistics with T-Mobile leading the adoption.

![](/images/5G%20chart.PNG)

Phew, a lot to consider from an internet service perspective. After investing in our workstation from a computing perspective, ensuring adequate battery capability, and providing fast charging from multiple sources, it’s time to figure out the network to power all this.

Both Starlink and 5G are at it’s infancy. The main issue of using Starlink in van-life is the lack of backwards compatibility against a more reliable network like 4G for metrics like uptime. For people van-lifing in rural areas however, 4G coverage is non-existant in the first place so Starlink is the logical choice.

Within the 4G/5G space, backwards compatible hotspots options provide the best of both worlds option with 5G when available and 4G as backup. The price point of 5G + 4G compatible vs just 4G is $500 vs $250. Starlink price points are comparable at $500 for the initial kit. Both unlimited data plans for Starlink and carriers run at around $100 a month.

My plan is to go with a Starlink reservation for testing and returns if necessary. The main workhorse is to opt for a backwards compatible 4G/5G router that is untethered to any major network. This allows for switching in the future as different providers grow into greater and greater 5G coverage.

**Conclusion:**

Hopefully, this article gives a high level overview of the decisions in creating a high performance van-life work setup for tech work. This setup is also perfect for running GPU heavy workloads locally like video processing and machine learning. This will allow your remote work performance to match that of any office worker and provide structure to onboard additional technologies in the future like AR/VR setups, IoT van sensors, and real-time applications running locally!
