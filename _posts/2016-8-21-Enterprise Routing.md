---
layout: post
title: Enterprise Routing
description:
image: assets/images/pic05.jpg
---
At this stage I was quite tired of Unifi/Edge appliances and wanted to take the more Enterprise route with routing and switching. I tore down the rack and sold pretty much everything and started a new.

I picked up a Watchguard XTM 515 off Ebay for quite cheap as the seller didn't really know what he was selling. I loaded pfSense on it, set up VLANs for my servers and services and a network for my roommates. It came with a 2 core Intel Celeron E3400 with 2GBs of RAM which wasn't sufficient to handle the 1Gb of traffic my roommates and I would saturate daily. Had to upgrade to a Intel Core2Quad Q9505 and 4GBs of RAM so that it could run quieter. I painted the Watchguard chassis black because the original red didn't fit the aesthetic of the rack.

I wanted the option to expand to 10G networking for my NAS and desktop PC so I purchased a Mikrotik CSS326 switch featuring two 10G SFP+ ports.
