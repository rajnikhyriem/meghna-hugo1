---
title: 'The Network Layer : Logical Addressing(Part 1)'
date: 2020-06-18T22:00:00+05:30
image_webp: "/images/adobe_post_20200618_1341300-8644540934043697.png"
image: "/images/adobe_post_20200618_1341300-8644540934043697.png"
author: Rajni Khyriem
description: ''
menu:
  main:
    name: RK's classroom
    weight: 1

---
      The network layer is responsible for the delivery of individual packets from the source to the destination host. The major goals of a network layer are – (i) routing, (ii) congestion control and (iii) addressing. The three goals can be achieved by (i) knowing about the topology of the subnet, (ii) ensuring there is no overload on some communication lines and routers while leaving others idle, (iii) resolving in case of source and destination are in different networks.

**1. LOGICAL ADDRESSING**

       Network Addresses are always logical. They are software based addresses which can be changed by appropriate configurations. A network address always points to host / node / server or it can represent a whole network. Logical addresses are necessary for universal communications that are independent of underlying physical networks.

       Physical addresses are not adequate in an inter network environment where different networks can have different address formats. A universal addressing system is needed in which each host can be identified uniquely, regardless of the underlying physical network.

      However, something to note is that no two publicly addressed and visible hosts on the Internet can have the same IP address.

**_1.1 IPv4 Addresses_** 

      An IPv4 address is a 32-bit address that uniquely and universally defines the connection of a device to the Internet. Every host and router on the Internet has an IP address. The IP address encodes its network number and host number. IPv4 addresses are 32 bits long and are used in two fields of IP packets – source address and destination address. IP address does not actually refer to a host. It really refers to a network interface. The IPv4 addresses are unique and universal.

**_1.1.1 IPv4 Addresses – Address Space_** 

     A protocol such as IPv4 that defines addresses has an address space. An address space is the total number of addresses used by the protocol. If a protocol uses N bits to define an address, the address space is 2 N . IPv4 uses 32-bit addresses, which means that the address space is 2 32 or 4,294,967,296 (more than 4 billion).

**_1.1.2 IPv4 Addresses – Notations_**

_In binary notation, the IPv4 address is displayed as 32 bits._ 

01110101 10010101 00011101 00000010

_In decimal dotted notation, the IPv4 address is displayed as 4 decimal numbers separated by dots._ 

192 . 168 . 20 . 5

Now that we have talked about IPv4 Addresses, let's try out a small exercise!

![](/images/untitled.png)