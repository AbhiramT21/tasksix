# Task Six: Packet Capture and Analysis with Wireshark

## Objective
Capture and analyze ICMP packets using Wireshark in Kali Linux, ensuring only four ICMP requests and responses are present.

## Commands and Features

1. **Ping Command:**
   - To send four ICMP Echo Requests:
     ```bash
     ping -c 4 google.com
     ```

2. **Wireshark Features:**
   - **Filter:** Use the display filter `icmp` to isolate ICMP packets.
   - **File Name:** Save the capture file as `ping.pcapng`.

## Repository Instructions

1. **Clone the Repository:**
   - If you need to clone a repository containing scripts or configurations related to this task, use:
     ```bash
     git clone https://github.com/AbhiramT21/tasksix.git
     cd tasksix
     ```

2. **Open the Capture in Wireshark (Optional):**
   - To review the uploaded capture file from the `tasksix` folder, use:
     ```bash
     wireshark ping.pcapng
     ```

## Notes
- Use the display filter `icmp` in Wireshark to isolate ICMP packets.
