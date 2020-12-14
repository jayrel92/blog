---
layout: post
title: First Rack
description:
image: assets/images/pic04.jpg
---

I lucked out and found a Startech 12u 4 post rack on r/homelabsales for $100. This would let me use real rails to mount my full depth servers, and clean up a lot of the cable management. At this point I added a UPS to keep the network and wifi AP up during storms.

To accommodate for hardware I plan on using I upgraded to a 24-port Unifi Switch. I also ended up getting a 1u rackmount for my EdgeRouter. Next I purchased a Supermicro 502-200B Atom D525 to run as intro into FreeBSD routing, testing OpenSense and pfSense. Finally ditched the Node 202 as a media PC to run OpenMediaVault/Plex (OMV) on a Rock64 4GB SBC. Linked to a TerraMaster DAS with 2x 3TB WD Red drives in Raid0 and 3x 2TB Toshiba drives in Raidz1 as backup. The Node 202 was deployed as an Assetto Corsa Dedicated Server hosting up to 32 concurrent drivers and cars 24/7 for about six months. The Raspberry Pi still doing its thing running piHole.

Here you can see that I did a bit more organizing of the rack. To accommodate a monitor and keyboard as my KVM console I moved my wifiAP to a more central location on the wall in my room. I added a 1U brush panel to allow some cables to pass through to the EdgeRouter.

The 1" flat CAT6 cables looked like spaghetti and made the rack untidy. I had to look for another shorter high quality ethernet cables.

I kept this setup for a few months learning VMWare ESXi/vSphere on the Dell servers but they were loud, power hungry. To cut down on noise and power I decided to go the Whitebox route for a new ESXi Host and NAS.
