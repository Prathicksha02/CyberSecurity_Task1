# Task 1

## Objective:
To perform basic network reconnaissance using Nmap and Wireshark to discover open ports, capture network traffic, and understand exposure of devices in the local network.

---

## Scanning

Scanning is the process of discovering active devices, open ports, and running services within a network. It helps in identifying potential vulnerabilities and understanding the network's exposure.

Using tools like **Nmap-Network mapper**, scanning allows security professionals to:

- Detect live hosts on the network
- Discover open ports and the services running on them
- Assess possible security risks from exposed ports
  
---

## Use of Finding Open Ports

Open ports indicate services that are accessible on a network. Identifying open ports is essential for:

- Detecting active devices and services
- Preventing unauthorized access
- Reducing security vulnerabilities
- Understanding potential attack vectors
- Improving overall network security

By scanning for open ports, organizations can monitor and secure their networks effectively.

---

## Tools Used:
- **Kali Linux**
- **Nmap** - For Port Scanning
- **Wireshark** - For Packet Capture and Analysis
- **VirtualBox** - To run Kali Linux VM
- **Windows 11** - Host System

---

## Steps Performed:

1. **Set Up Kali Linux** in Bridged Adapter mode to connect to the local network.
2. Found local IP range using: **ifconfig**
3. Ran TCP SYN Scan with Nmap: **nmap -sS 192.168.164.0/24**
4. **We were able to see the open ports such as:** 53/tcp (DNS), 5555/tcp
5. Saved scan results to: **scan_results.txt**
6. Captured network traffic using Wireshark during the Nmap scan.
7. Exported packet details from Wireshark to: **packet_details.txt**
8. Total packets found in the wireshark: 4547
9. Transferred files to Windows host using VirtualBox Shared Folder.

---

## Files Included:
 __ __ __ __ __ __ __ __ __ __ __ __ __ __ __ __ __ __ __ __ __ __ __ _
| File Name             | Description                                  |
|-----------------------|----------------------------------------------|
| scan_results.txt      | Nmap scan output showing open ports          |
| packet_details.txt    | Wireshark exported packet dissection details |
| Screenshots_Task1.pdf | Screenshots showing practical steps          |
|__ __ __ __ __ __ __ __|__ __ __ __ __ __ __ __ __ __ __ __ __ __ __ _|

---

## Observations:

- Successfully discovered active devices in the local network.
- Identified open ports and potential running services.
- Verified SYN packets in Wireshark capture.
- Understood basic exposure risks due to open ports.

---

## Conclusion:

This task provided hands-on experience with:
- Network Scanning using Nmap
- Traffic Capture using Wireshark
- Recognizing the importance of monitoring open ports to secure networks



