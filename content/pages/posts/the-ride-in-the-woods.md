---
title: 'QR_ERP: Automated Cloud Based Inventory Control'
excerpt: >-
  QR ERP is a cloud based supply chain app for inventory management. QR codes
  are used to automate the tracking of inbound and outbound inventory versus
  floor level excel systems. The tracked inventory is automatically deployed
  into SQL data connection.
date: '2018-01-23'
thumb_img_path: /images/QR ERP.png
thumb_img_alt: 
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
---
QR ERP is a product demo for a cloud based QR scanning system. Small manufacturing facilities need an inventory tracking solution that is lightweight, fast, and accessible without all the expensive bells and whistles that large ERPs typically come with. With our setup, small manufacturing factories can print QRcodes as action modules and auto-increment inventory, reconcillate warehouse stock, and create full builds via Bill of Materials with their phone! The Azure SQL solution also makes it easy to maintain and keep track of existing tables to update future functionality. This provides an end-to-end inventory, warehouse, and logistics solution within a single hosted azure app (Figure 1)

Figure 1: End to End Inventory flow
<img width="863" alt="QR ERP BG" src="https://user-images.githubusercontent.com/16582383/118562065-df697900-b720-11eb-9fa6-c8a76dfc289c.PNG">

To run the flask app, clone the repo and run app.py inside the main App folder. A cloud database setup comes with a bit more work. To begin you need an azure account. Contact cloud@optimchain.org to see how we can help you setup your backend! (Figure 2)

