# Task Six

## Overview

This repository contains the results of a packet capture performed using Wireshark on Kali Linux. The capture was conducted while pinging `google.com` to demonstrate ICMP traffic. The capture file includes exactly four ICMP Echo Request and four ICMP Echo Reply packets.

## Packet Capture Details

The packet capture was performed using the following steps:

1. **Start Wireshark:**
   - Open Wireshark from the applications menu or by typing `wireshark` in the terminal.

2. **Start Packet Capture:**
   - Select `eth0` (or the appropriate network interface) from the list of available interfaces.
   - Click on the "Start capturing packets" button (the green shark fin icon) to begin capturing network traffic.

3. **Execute Ping Command:**
   - Open a terminal window.
   - Send four ICMP Echo Request packets to `google.com` using the following command:
     ```bash
     ping google.com -c 4
     ```

4. **Observe Captured Packets:**
   - In Wireshark, apply a filter to display only ICMP packets.
   - Confirm that there are exactly four ICMP Echo Request packets and four ICMP Echo Reply packets.

5. **Save the Capture File:**
   - Go to `File` > `Save As` in Wireshark.
   - Save the capture file with the name `ping.pcapng`.

6. **Upload to GitHub:**
   - Navigate to the `tasksix` directory in your GitHub repository.
   - Upload the `ping.pcapng` file to this directory.

## Files

- **`ping.pcapng`**: Contains the captured ICMP packets from the ping test. This file includes four ICMP Echo Requests and four ICMP Echo Replies.

## Instructions

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/AbhiramT21/tasksix.git

2. Navigate into the repository directory:

    bash
    Copy code
    cd tasksix
    Open ping.pcapng with Wireshark to view the captured ICMP packets:

3. Launch Wireshark.
    Go to File > Open.
    Select ping.pcapng to open the file and analyze the packets.
