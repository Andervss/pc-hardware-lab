# PC Hardware Lab

A hands-on PC hardware learning project covering component identification, maintenance, disassembly, reassembly, and troubleshooting.

## About

This repository documents practical hardware work carried out on an older Advent DT2412 desktop PC.

The aim is to build familiarity with PC components and gain hands-on experience working inside a desktop computer.

## System

| Component | Specification |
|---|---|
| PC | Advent DT2412 |
| CPU | Intel Core i7-3770 |
| RAM | 16 GB |
| Storage | 2 TB HDD |
| GPU | NVIDIA GTX 960 |
| Original GPU | NVIDIA GT 630 |

## What I Did

- Removed and reseated all four RAM sticks
- Removed and reinstalled the GTX 960
- Removed the 2 TB HDD
- Removed the optical drive
- Inspected the motherboard, PSU and internal cabling
- Cleaned dust from the system, including around the CPU cooler
- Reassembled the PC and tested that it booted normally

### Tools

- Phillips screwdriver
- Compressed air
- Small container for screws

I kept the screws organised according to where they came from so I knew where they needed to go during reassembly.

## What I Found

Before starting, the PC was extremely slow during normal use.

Task Manager showed the HDD reaching **100% active time**, with relatively high response times. This suggested that the mechanical HDD was likely contributing significantly to the poor performance.

## Challenges & Lessons Learned

- **GPU removal:** The PCIe retention clip was harder to release than expected. I initially underestimated how far the lever needed to be pressed.

- **Optical drive:** I initially assumed the optical drive would need to be removed from inside the case. I later realised that the front panel came off easily and the drive slid out through the front.

- **24-pin motherboard power:** The main 24-pin connector was difficult to disconnect and required careful handling of the locking mechanism.

- **HDD removal:** The 2 TB HDD was mounted inside a drive cage. Part of the case had to be removed before the drive could be released and slid out.

- **Reassembly:** After putting everything back together, the PC powered on for a moment before shutting down. I found that the **JPWR2 CPU power connector** had not been reconnected. After reconnecting it, the PC booted normally.

## Result

The PC was successfully reassembled and returned to its previous working condition.

The original performance problem remains, with the mechanical HDD appearing to be a significant bottleneck.

## Future

I plan to use the PC for further hardware learning and troubleshooting exercises.
