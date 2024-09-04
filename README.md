# Overview
This project contains the tools necessary to integrate a simple, free, non-rigorous implementation of Zero-Trust Networking (ZTN) concepts in a home network space. 
Any users implementing this guide should be aware that installing [OpenWRT](https://openwrt.org/start) will void most (if not all) router warranties. This project was part of University of Oregon's Computing Security II course. 

## This project is perfect for you if: 
- You are a relatively non-invested network admin of your home network
- You have a simple consumer router (you aren't crazy homelabbing it with pfSense and load balancers and Fortigates)
- You are curious about what Zero Trust actually means (me too)

## Zero Trust: What does it mean here?

It's relatively simple. We aren't using trust brokers, we aren't overengineering the network components nor hardware, etc. What we are doing is assuming
that most network operators of home networks are only minorly interested (or fully uninterested) in their own netsec and trust that the factory defaults and router capabilities are
sufficient for all use cases. Perhaps some of them might be willing to spend a little bit of time investigating what security really means. With the advent of botnets and the failing of early 
early IoT security, it would not be a stretch to say that many home networks are already compromised. In this case, ZTN can be massively useful.

# The Beginning
There are two avenues that the user can leverage:
- No OpenWRT
- OpenWRT

Installing OpenWRT is the more intensive, technical, and potentially dangerous option. Regardless, it's pretty cool and allows the majority of the tools to be installed at the best possible location
on the network. 

# What This Project Is
This project is essentially a guide/report on the steps needed to implement key ZTN concepts on a home router. Please see REPORT.pdf for more.

