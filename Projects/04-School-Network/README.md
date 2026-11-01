# School Network - Device Connectivity and Switch Monitoring

## Overview

After completing my previous projects, I wanted to take my networking practice a step further by building a simulated school network. In this project, I began developing a functioning network that represents the infrastructure commonly found in a school environment. 

I started by integrating a TP-Link TL-SG108E 8-port Gigabit Easy Smart Switch with the 12-port patch panel I had configured in [project 03-Patch-Panel-Termination](../03-Patch-Panel-Termination). The objective was to understand how switches connect devices on a local area network (LAN), practice IPv4 addressing, verify communication between devices, and monitor network activity.

I used my MacBook Pro and iPad Pro to simulate two devices connected through separate Cat6 cable runs and keystone jacks. I assigned each device a static IPv4 address on the same subnet and used Terminal commands such as ifconfig, ping, and arp to verify network configuration and connectivity. 

I also accessed the switch's web management interface to examine port status, negotiated link speeds, and packet statistics. By generating ICMP traffic between the two devices and comparing the switch's transmit and receive counters, I practiced observing how Ethernet traffic moves through a switched network.

## Equipment Used
  * TP-Link TL-SG108E 8-port Gigabit Easy Smart Switch
  * 12-port patch panel
  * RJ45 Ethernet patch cables
  * MacBook Pro
  * iPad Pro
  * USB-C to Gigabit Ethernet adapters (x2)

This project builds on the patch panel and existing Cat6 cabling configured and tested in [Project 03-Patch-Panel-Termination](../03-Patch-Panel-Termination).

## Network Topology














