# Task Six: Packet Capture and Analysis with Wireshark

## Objective
Capture and analyze ICMP packets using Wireshark in Kali Linux, ensuring only four ICMP requests and responses are present.

## Instructions

1. **Open Wireshark:**
   - Launch Wireshark from the applications menu or by typing `wireshark` in the terminal.

2. **Start Packet Capture:**
   - Select the network interface `eth0` from the list of available interfaces.
   - Click the **Start Capturing Packets** button (shaped like a shark fin).

3. **Ping Google:**
   - Open a terminal window.
   - Execute the following command to send four ICMP Echo Requests:
     ```bash
     ping -c 4 google.com
     ```

4. **Observe Packets in Wireshark:**
   - Go back to Wireshark.
   - In the packet list pane, look for ICMP packets. You should see:
     - Four ICMP Echo Request packets.
     - Four ICMP Echo Reply packets.

5. **Verify Packet Count:**
   - Ensure that the capture shows exactly four ICMP requests and four ICMP responses.
   - Use Wireshark's filter `icmp` to focus on ICMP packets only.

6. **Stop Capture:**
   - Once you have observed the packets, click the **Stop Capturing Packets** button (red square).

7. **Save the Capture:**
   - Go to **File > Save As** in Wireshark.
   - Save the file with the name `ping.pcapng`.

## Notes
- Use the display filter `icmp` in Wireshark to isolate ICMP packets.

## Working with GitHub Repository

1. **Clone the Repository:**
   - If you need to clone the repository containing scripts or configurations related to this task, use:
     ```bash
     git clone https://github.com/AbhiramT21/tasksix.git
     cd tasksix
     ```
     
