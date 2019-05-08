---
layout: post
author: Steven Buehler
title: "Software-Defined Radio: ACARS and VDLM"
date: 2019-05-08T11:58:09-04:00
---
Living within a mile and a half of a major airport and owning an [RTL-SDR](http://www.rtl-sdr.com) device has its rewards&mdash;namely, being able to monitor aircraft activity close by for fun. 

There are essentially four types of information that can be gleaned using Software-Defined Radio (SDR) when living near an airport:

* Air band voice chat and Air Traffic Control (ATC) between airport and air center personnel and aircraft pilots and personnel over AM VHF frequencies in the 118 MHz to 137 MHz frequency band (some airlines offer a channel on their in-flight audio to listen in on Air Traffic Control voice channels during the flight, which I've always found interesting);

* Automatic Dependent Surveillance-Broadcast (ADS-B), which transmits digital location, heading, and speed data from nearby aircraft, usually at 1090 MHz (another service, ADS-C, receives on 978 MHz and is used typically by smaller aircraft);

* Aircraft Communication Addressing and Reporting System (ACARS), which exists as an rudimentary "email" service of sorts, where messages and aircraft data such as configuration messages and event data can be sent and received between aircraft and ground controllers (nearby TPA uses 131.550 MHz and 131.725 MHz for the protocol);

* The successor to ACARS, called VHF Data Link - Mode 2 (VDL2), that is similar to ACARS but is about ten times faster and provides more services to pilots and ground controllers. Southwest Airlines (SWA), TPA's largest carrier by traffic, uses VDL2 on 136.975 MHz in place of ACARS, which is why most aviation buffs monitoring ACARS traffic never see transmissions from SWA aircraft.