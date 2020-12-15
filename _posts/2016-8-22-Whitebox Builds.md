---
layout: post
title: Whitebox Builds
description:
image: assets/images/pic17.jpg
---
I quickly got rid of the 1" flat CAT6 cables and replaced them with .5" Monoprice Slim Run cables.

Below the Unifi switch is my ESXi server. Built inside an iStarUSA 2U chassis.

At the time it had 32GB of DDR3 RAM, I7 3770s CPU which is and 4 core with hyperthreading giving them 8 threads each. This means in my ESXi server I have 4 cores and 8 threads to play with. This is not much CPU power but sufficient for small application needs. This server has 2x 1TB & one 2TB drive in the front for VM storage. Inside there is one 2.5" Micron Enterprise 500GB SSD in the server for ESXi boot.

It runs ESXi 6.7, on there I have vCenter, a docker host with a few containers (for Grafana lives, as well as other things like Airsonic), a few Windows VM's for pen-testing labs and a windows server domain controller that I access over RDP.

Next up we have my Freenas server, which has a X10SDV-8C+-LN2F in it which gives me 10G connectivity. In order to keep things quiet it is a Xeon-D SOC with 32GB of Reg. ECC DDR4 housed in a iStarUSA M-140-ITX 1U chassis. I bought that motherboard with the intention of going to 10G in the future. It had 4x 3TB WD Red hard drives RAIDz1 array which gives me about 8TB of capacity with 3TB of redundancy. This NAS runs PLEX and Tautulli for media. Next below the NAS is a Dell R210ii which I used for my Assetto Corsa Dedicated server.
