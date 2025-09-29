# Capture-and-Analyze-Network-Traffic-Using-Wireshark.# Wireshark Packet Analysis Lab

## 📌 Overview
This repository documents a hands-on lab using **Wireshark** to capture, filter, and analyze network packets.  
The goal is to develop **packet analysis skills** and gain awareness of common network protocols.

## 🎯 Learning Outcomes
- Capture live network traffic
- Apply protocol filters (HTTP, DNS, TCP, ICMP, etc.)
- Identify at least 3 protocols in a capture
- Export capture files as `.pcap`
- Summarize findings with packet details
- Document analysis using screenshots

## 📂 Repository Contents
- `lab_instructions.md` → Step-by-step Wireshark lab procedure  
- `findings.md` → Summarized results & analysis  
- `captures/` → Sample `.pcap` file(s)  
- `screenshots/` → Screenshots of Wireshark captures and analysis,
- C:\Users\msyam\Downloads\task5
-  `references.md` → Useful references and resources  

## 🚀 Quick Start
1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/wireshark-packet-analysis-lab.git

---

# 📝 lab_instructions.md

Contains the **step-by-step instructions** you listed earlier:

```markdown
# Wireshark Lab Instructions# Lab Findings

## 📊 Capture Summary
- Total packets captured: ______
- Capture duration: ______

## 🌐 Protocols Identified
1. **DNS**
   - Example: Query for `google.com`
   - Src: 192.168.1.___
   - Dst: 8.8.8.8
   - Port: 53 (UDP)

2. **HTTP**
   - Example: GET request to `example.com`
   - Src: 192.168.1.___
   - Dst: 93.184.216.34
   - Port: 80 (TCP)

3. **ICMP**
   - Example: Ping request/reply
   - Src: 192.168.1.___
   - Dst: 142.250.190.78 (Google)

## 📝 Observations
- Most web traffic was HTTPS (encrypted).
- TCP 3-way handshake observed.
- DNS resolution occurred before HTTP requests.

---


1. Install Wireshark: [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)
2. Start capturing on your active network interface.
3. Browse a website or run `ping google.com` to generate traffic.
4. Stop capture after about a minute.
5. Filter by protocols:
   - `http`
   - `dns`
   - `tcp`
   - `icmp`
6. Identify at least 3 different protocols.
7. Export as `.pcap` → save in `captures/`.
8. Summarize findings in `findings.md`.

---
# References

- [Wireshark Official Website](https://www.wireshark.org/)
- [Wireshark User’s Guide](https://www.wireshark.org/docs/wsug_html_chunked/)
- [Wireshark Wiki](https://gitlab.com/wireshark/wireshark/-/wikis/home)
- [Packet Analysis with Wireshark (Tutorial)](https://www.varonis.com/blog/wireshark-tutorial)



