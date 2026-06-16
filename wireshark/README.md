# Wireshark Network Traffic Analysis

## Overview

This section contains packet analysis activities performed using Wireshark. The captures were generated in a controlled lab environment to understand how reconnaissance and service enumeration can 
be identified from network traffic.

The objective of this project is to demonstrate the ability to inspect packets, identify attacker behavior, and document findings from packet captures.

## Scenario

A simulated attacker host attempted to discover services running on a target system. Multiple reconnaissance techniques were observed, including:

* TCP SYN scanning
* SSH service discovery
* SSH version and host key enumeration
* Packet correlation between attacker and victim

## Skills Demonstrated

* Packet inspection using Wireshark
* Traffic filtering with display filters
* Identification of reconnaissance techniques
* Analysis of TCP handshakes
* Documentation of findings
* Understanding of SSH communication patterns

## Directory Structure

```text
wireshark/
├── analysis/      # Written findings and interpretation of packet captures
├── file.pcap/     # Packet capture files used during the investigation
├── images/        # Screenshots supporting the analysis
└── README.md
```

## Key Findings

* The attacker performed TCP SYN scans against multiple ports on the target.
* SSH service discovery activity was identified.
* Nmap NSE scripts were observed during SSH enumeration.
* Traffic patterns were analyzed to understand attacker behavior during the reconnaissance phase.

## Disclaimer

All activities presented in this repository were conducted in a personal laboratory environment for educational and defensive security purposes only.

