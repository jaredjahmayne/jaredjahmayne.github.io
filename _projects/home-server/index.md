---
layout: post
title: TrueNAS Home Lab & Game Server
description: Built and configured a dedicated Linux server for redundant network storage, media streaming, and hosting multiplayer game instances.
skills: 
  - TrueNAS Scale
  - Docker & Containerization
  - Networking (DNS/VPN)
  - ZFS File Systems
  - Linux Administration
main-image: /home-server-setup.jpg
---

### **Project Overview**
I built a dedicated home server to gain hands-on experience with enterprise-grade networking and virtualization. The system runs on **TrueNAS Scale**, serving as a central hub for data backup, media streaming, and hosting persistent game servers for friends.

### Technical Implementation**
* **Storage Architecture:** configured a ZFS storage pool with redundancy (RAID-Z) to ensure data integrity for personal files and engineering projects.
* **Containerization:** utilized Docker containers to deploy and manage various services, isolating them from the core OS for better stability and easier updates.
* **Game Server Hosting:** configured dedicated servers for **Assetto Corsa** and other titles. This involved managing port forwarding, optimizing tick rates for low latency, and setting up automated restarts.
* **Network Services:** deployed **Pi-hole** for network-wide ad blocking and local DNS resolution, and set up **WireGuard** to securely access the home network and files remotely.

### **Hardware Config**
* **OS:** TrueNAS Scale (Linux-based)
* **Storage:** IronWolf NAS Drives running in ZFS Pool
* **Memory:** ECC RAM for error correction and data stability
