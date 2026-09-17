# Wi-Fi Packet Capture and Analysis

## Overview

This project documents a Network Forensics mid-term lab focused on capturing and analyzing live wireless traffic using **Wireshark** and **Acrylic Wi-Fi Sniffer**.

The original lab focused on:
- Capturing live Wi-Fi packets
- Understanding how wireless traffic moves
- Reading packet details
- Comparing normal and advanced capture
- Using Acrylic Wi-Fi Sniffer with Wireshark
- Following basic digital-forensics data-acquisition stages

## Tools Used

### Wireshark
Used to capture and analyze network packets.

### Acrylic Wi-Fi Sniffer
Used to place the Wi-Fi adapter in monitor mode and help Wireshark capture wireless packets.

## Main Goal

The goal of the lab was to use Wireshark and Acrylic Wi-Fi Sniffer to capture live wireless packets, understand how Wi-Fi traffic moves, read packet details, and compare normal and advanced capture.

## Key Observations

During the lab, Acrylic displayed nearby wireless networks and their connection information. The report also documented a personal network quality observation of **6/10** and noted that the security and speed did not meet the student's preference.

The report describes Wireshark as more difficult to read at first, while Acrylic presented wireless information in a more structured way.

## Forensic Data-Acquisition Stages

1. **Identification** — Identify where the data is coming from, such as the Wi-Fi adapter or device.
2. **Preservation** — Keep the data safe and avoid changing or deleting it.
3. **Acquisition** — Capture the data using tools such as Wireshark and Acrylic.
4. **Verification** — Check that the data is authentic and has not changed by saving and hashing the file.

## What I Learned

Using Acrylic with Wireshark helped me understand how Wi-Fi works in a real environment. I was able to see how devices communicate with the router and how data travels wirelessly.

The lab also showed how network-capture tools can support forensic work by allowing traffic to be collected and studied as evidence.

## Future Improvements

For a future version of this project, I can add:
- Packet-capture screenshots
- Wireshark display filters
- Specific packet examples
- Protocol observations
- A saved `.pcap`/`.pcapng` sample where appropriate
- Hash values for captured evidence
- A more detailed timeline of the capture

## Academic Source

The original project was completed as a **Network Forensics** course mid-term report.

Instructor: Emerson  
Date: October 25, 2025

> This GitHub repository is a portfolio version of the original course work. It is intended to demonstrate learning and hands-on experience.
