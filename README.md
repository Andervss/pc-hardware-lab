# PC Hardware Lab

A hands-on PC hardware learning project covering component identification, maintenance, disassembly, reassembly, and troubleshooting.

## About

This repository documents practical hardware work carried out on an older **Advent DT2412** desktop PC.

The aim is to build familiarity with PC components and gain hands-on experience working inside a desktop computer, including identifying components, removing and reconnecting hardware, cleaning, and troubleshooting issues after reassembly.

## System

| Component    | Specification      |
| ------------ | ------------------ |
| PC           | Advent DT2412      |
| CPU          | Intel Core i7-3770 |
| RAM          | 16 GB              |
| Storage      | 2 TB HDD           |
| GPU          | NVIDIA GTX 960     |
| Original GPU | NVIDIA GT 630      |

## Exercise 01 — PC Teardown & Reassembly

### Objective

Gain hands-on experience identifying, removing, and reinstalling PC components.

### What I Did

* Removed and reseated all four RAM sticks
* Removed and reinstalled the GTX 960
* Removed the 2 TB HDD
* Removed the optical drive
* Inspected the motherboard, power supply, and internal cabling
* Cleaned dust from the system, including around the CPU cooler
* Reassembled the PC
* Booted the system and checked that it was functioning normally

### Initial Performance

Before starting the teardown, the PC was noticeably slow during normal use.

Task Manager showed the HDD reaching **100% active time**, with relatively high response times. This suggested that the mechanical HDD was likely contributing significantly to the poor performance.

The purpose of the teardown was not to replace any components, but to gain practical experience working inside a desktop PC.

### Challenges & Lessons Learned

A few parts of the teardown were less straightforward than I initially expected:

* **GPU removal:** The PCIe retention clip was harder to release than expected. I initially underestimated how far the lever needed to be pressed before the GPU could be removed. This helped me understand how the PCIe retention mechanism works and the importance of checking how a component is secured before applying force.

* **Optical drive:** I initially assumed the optical drive would need to be removed from inside the case. I later realised that the front panel could be removed easily and the drive was designed to slide out through the front.

* **24-pin motherboard power:** The main 24-pin motherboard power connector was difficult to disconnect. This showed me how firmly some connectors can be seated and the importance of understanding the locking mechanism before attempting to remove them.

* **HDD removal:** The 2 TB HDD was mounted inside a drive cage. The relevant part of the case had to be removed before the drive could be released and slid out. This helped me understand how storage drives can be secured differently depending on the case design.

### Reassembly Troubleshooting

After reassembling the PC, it powered on briefly before immediately shutting down.

I checked the internal connections and found that the **JPWR2 CPU power connector** had not been reconnected.

After reconnecting JPWR2, the PC booted normally.

This reinforced the importance of checking all power and component connections when troubleshooting a system that fails to start after hardware work.

### Result

The PC successfully booted and all components appeared to be functioning normally.

The original performance issues remained, with the mechanical HDD still appearing to be a significant bottleneck during normal use.

## What I Learned

* Identifying the main components inside a desktop PC
* Understanding basic motherboard power connections
* Understanding PCIe GPU retention mechanisms
* Safely removing and reseating RAM and a GPU
* Disconnecting and reconnecting storage and optical drives
* How different case designs secure internal components
* Basic internal PC maintenance and dust cleaning
* Troubleshooting a PC that fails to remain powered on after reassembly
* The importance of checking every connection when rebuilding a PC

## Future Exercises

* [ ] Identify and document motherboard connectors
* [ ] Learn more about PSU cables and power delivery
* [ ] Investigate the HDD performance issue
* [ ] Learn how to diagnose common hardware faults
* [ ] Explore BIOS/UEFI hardware detection and settings
* [ ] Document additional hardware troubleshooting exercises
