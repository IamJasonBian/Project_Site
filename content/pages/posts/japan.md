---
excerpt: >-
  SwingTech is a motion tracking IoT device built to generate motion analytics
  for swing sports. Machine Learning algorithms parse swings through
  acceleration, classify swing type, and plot all swings for easy visualization.
date: '2019-03-24'
thumb_img_path: /images/SwingTech.png
thumb_img_alt: SwingTech Product Pic
content_img_alt: SwingTech Product Pic
seo:
  title: Swingtech
  description: >-
    The Shrines of Ise have been celebrated as the prototype of Japanese
    architecture
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: A Weekend in Japan
      keyName: property
    - name: 'og:description'
      value: >-
        The Shrines of Ise have been celebrated as the prototype of Japanese
        architecture
      keyName: property
    - name: 'og:image'
      value: images/2.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: A Weekend in Japan
    - name: 'twitter:description'
      value: >-
        The Shrines of Ise have been celebrated as the prototype of Japanese
        architecture
    - name: 'twitter:image'
      value: images/2.jpg
      relativeUrl: true
layout: post
title: SwingTech
---
### Swingtech is a Sensoring based solution for Swing Analytics

At its core, Swingtech allows you to record a series of motion swings, download them into your local desktop (Figure 1), and visualize the swing trajectories of those swings (Figure 2).

*   SwingTech site: https://swingtech.io/
*   SwingTech github: https://github.com/IamJasonBian/SwingTech_Core

Figure 1: SwingTech Captured Swings

![image](https://user-images.githubusercontent.com/16582383/119071386-8f97e580-b99e-11eb-9217-fe57bb822b4e.png)

Figure 2: SwingTech Swings Deep-Dive

Here, we can see the orientation time-series, the acceleration time-series, and the displacement time-series projected and within the xyz plane.

![image](https://user-images.githubusercontent.com/16582383/119071697-249ade80-b99f-11eb-85eb-0f288cf21918.png)

### Building the Device:

At the bare minimum, the following set of items is needed to assemble the device:

1.  pi zero
2.  sd card
3.  yoctopuce sensor
4.  micro usb connection
5.  pi zero power supply

We 3d printed an enclosure for this device and its specs can be found in this whitepaper: https://swingtechio.files.wordpress.com/2020/02/project-doc.pdf

Additionally, you can request beta devices here:
https://docs.google.com/forms/d/e/1FAIpQLSdCNZfaUu4nQ0SYeTc7iaQ_SiNzVzpYLAXgBIuaWSeN1zN-\_g/viewform

### Using the Beta Build

To use the beta build, fork the pi-test into your raspberry pi and download the pi-build repo into your pi. Within pi-build there are two possible scripts you can use via init scripts within the pi:

1.  anydot.py: The build will auto record once the pi is live
2.  mydot.py: The build will record according to commands from bluedot: https://bluedot.readthedocs.io/en/latest/

To run the App, fork the Desktop App contents into your Desktop. If you wish to view the contents of the pi, plug it via usb into your computer and use the Usb_Copy.py code to locally save pi data into your computer. Make sure to move the contents of the usb transfer into the Assets folder as Data.csv.
