---
title: "My homelab"
author: "Aron Emanuel Kylebäck"
date: 2024-06-20
---
## Introduction
What is a homelab? Why do I have one? What's in it?

I'll answer these questions and more in this post, and explain my plans for the future.

## What is a homelab
Simply put a homelab is a setup of computer and networking equipment in a person's home used for learning, experimenting, and hosting personal projects or websites. It can range from a single computer to a complex network of servers and devices.

## What do I run
My hypervisor of choice is Proxmox, on said hypervisor I run different VMs using debian.
The primary VM is running Docker compose, all of this together hosts:
- Jellyfin - A media library management system.
- qBittorrent - To torrent linux ISOs.
- Minecraft - Multiple minecraft severs, vanilla & modded.
- Homeassistant - Not configured yet, on my todo list.

## What's in it
- Huawei FusionServer 2288H V5 with a single Xeon Scalable 1st Gen Gold 5118, 2x16GB 2400MHz RAM, a single 870 evo 1TB and 2x DC600M 1920GB.
- Netgear Managed Switch.
- Raspberry Pi 4 (4gb) x 3.
- 3D Printer (Resin & FDM).

## What's next
- A new router - Most likely going to get a MikroTik, unsure what model, but possible one with 10G capabilities.
- A proper UPS - Call me crazy, but I would rather not lose everything if lightning strikes.
- A dedicated graphics card - Would be used for Jellyfin media transcoding, currently the Intel Arc A310 or A380 are my choice. I am waiting for the release of Battlemage to hopefully get a better price or even one of the new cards.
- More RAM - Self explanatory, 32GB is a lot, but 64 or even 128GB is the goal.