# DHCP Network Configuration using Cisco Packet Tracer

## Project Overview

This project demonstrates the configuration of a basic network using **DHCP (Dynamic Host Configuration Protocol)** in Cisco Packet Tracer.

A Cisco router is configured as a DHCP server to automatically assign IP addresses, subnet masks, default gateways, and DNS server information to multiple PCs connected through a switch.

The project also includes basic network connectivity testing and DHCP troubleshooting.

---

## Objectives

* Configure a Cisco router interface
* Configure a Cisco router as a DHCP server
* Automatically assign IP addresses to PCs
* Configure the default gateway and DNS server
* Configure DHCP excluded addresses
* Verify DHCP leases
* Test network connectivity using `ping`
* Troubleshoot an incorrect DHCP configuration

---

## Network Topology

```text
                  Router R1
              G0/0: 192.168.10.1
                       |
                       |
                    Fa0/1
                     SW1
                  /   |   \
                 /    |    \
               PC1   PC2   PC3
