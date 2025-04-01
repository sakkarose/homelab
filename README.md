# Homelab

## Overview

This homelab aims to create an environment for:

- Running a Wazuh stack in rootless Docker.

- Learning new operating systems.

- Testing security technologies, tools and approaches.

- Self-hosting personal applications.

## Infrastructure

| Device | Hostname | QuickSpecs | OS | Uses |
| -------- | -------- | -------- | -------- | -------- |
| Xiaomi CR8806 | 02-miya-openwrt | Qualcomm 1GHz<br>256MB RAM | OpenWrt 21.02 | WAN/WLAN router |
| Asus Aspire 3 | 01-mira-coreos | Ryzen 5 7520U<br>16GB RAM<br>512GB NVMe | Fedora CoreOS | Self-hosting applications with Quadlet pods |
| Asus Aspire 5 | 03-miso-debian | Core i5-1035G1<br>16GB RAM<br>512GB NVMe | Debian 12.10 | Wazuh stack |
| Raspberry Pi 3B+ | 04-mirae-ubuntu | BCM2837B0<br>1GB RAM<br>30GB SDHC | Ubuntu Server 24.04.2 LTS | Management/DNS server |
| TP-Link SF1008D | N/A | 8 10/100Mbps ports | N/A | Unmanaged switch for local-only devices |
| Surface Laptop 3 | 10-michi-w11ltsc | Core i5-1035G7<br>16GB RAM<br>256GB SSD | Windows 11 IoT Ent LTSC | Office workstation |
| ThinkPad E15 | 11-mikka-w11ltsc | Core i5-10200H<br>16GB RAM<br>512GB NVMe | Windows 11 IoT Ent LTSC | Home workstation |
| NEC LAVIE Direct HZ GN1643/4E | 13-miwa-voidmusl | Core i5-8250U<br>8GB RAM<br>512GB NVMe | Void Linux (musl) | Take-away laptop |
| Cloud VM | N/A | N/A | Alpine 3.21 | Hosting a few applications with rootless Docker (Currently in migration to another provider) |

### Work-in-Progress

- Infrastructure diagram

- Hoarder stack (Quadlet)

## Write-up

To-do
