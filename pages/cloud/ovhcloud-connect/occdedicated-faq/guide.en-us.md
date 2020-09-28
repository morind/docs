---
title: FAQ
slug: occdedicated-faq
excerpt: 'FAQ about the OVHcloud Dedicated Connect solution'
section: Getting started
order: 4
---

**Last updated 14th September 2020**

## OVHcloud Dedicated Connect FAQ

### What is the OVHcloud Connect solution designed for?

With OVHcloud Connect, you can link your company network to your private OVHcloud vRack network, without creating a VPN tunnel through the internet. This will give you a quicker, more stable connection with guaranteed bandwidth.

### Which products are compatible with OVHcloud Connect?

OVHcloud Connect is an extension of your OVHcloud vRack private network, so all products with the vRack feature enabled will be compatible.

### How do I choose between a Layer 2 or Layer 3 cross-connection for the OSI model?

You will need to keep in mind the features associated with Layer 2 and Layer 3 networks as you build your infrastructure, in order to select the best cross-connection for your hybrid cloud requirements.

#### Layer 2 OSI

The OVHcloud Connect solution dedicated to Layer 2 means that the connection is transparent to the Ethernet protocol.

The advantage of a Layer 2 connection is that it simplifies the way you connect your data centre’s campus network to your OVHcloud vRack private network. 

You will need basic knowledge of how to use LAN networks. 

Redundancy can be local within the same point of presence (PoP), using LACP 802.3ad protocol.

The virtual local area networks (VLANs) are the same in your data centre and within OVHcloud data centres.

#### Layer 3 OSI

The OVHcloud Connect solution dedicated to Layer 3 is a connection managed by routers. 

The advantage of a Layer 3 cross-connection is that you can connect your company’s WAN network to your OVHcloud vRack private network, so that it is considered as a site within your WAN network. 

You will need an advanced understanding of MAN and WAN networks, as well as knowledge of how to manage inter-network routing. 

Layer 3 networks require one or more private external BGP sessions to be established between the company and OVHcloud. 

Redundancy can be local within the same PoP, and geographical between two PoPs using BGP redundancy mechanisms.

The VLANs are **not** the same in your data centre and within OVHcloud data centres.

### Can OVHcloud host my routers?

OVHcloud does not host network hardware for customers in data centres and PoPs. Customers need to have their hardware hosted by an operator or by a third party, then request a connection to OVHcloud hardware in the MMR (meet-me room) of the PoP. Instructions on how to do this are provided in the Letter of Authorisation (LOA). 

### What connections are supported for OVHcloud Connect?

We support single-mode fibre optic. Your SFP/SFP+ must support either 1000LX/LH or 10G-LR.

## Go further

Join our community of users on <https://community.ovh.com/en/>.