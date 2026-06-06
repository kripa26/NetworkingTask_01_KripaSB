\# Networking Task 01: Understanding Your Network Environment



\## 📌 Project Overview

This project documents the basic network configuration and connectivity testing for my local workstation as part of the technical training program.



\## 💻 Part A: System Network Information

| Component | Details |

| :--- | :--- |

| \*\*Hostname\*\* | LAPTOP-KJ6JLATK |

| \*\*IPv4 Address\*\* | 10.55.194.141 |

| \*\*MAC Address\*\* | XX-XX-XX-XX-XX-XX (Masked for Security) |

| \*\*Default Gateway\*\* | 10.55.194.49 |

| \*\*DNS Server\*\* | 10.55.194.49 |



\---



\## 📖 Part B: Core Concepts

\* \*\*IP Address:\*\* A logical numerical identifier assigned to devices on a network using IP protocol for routing and data exchange.

\* \*\*MAC Address:\*\* A permanent, physical hardware identifier assigned to a network interface controller during manufacturing.

\* \*\*Default Gateway:\*\* The intermediate network node or router that local devices use to forward traffic to external networks or the internet.

\* \*\*DNS (Domain Name System):\*\* A hierarchical system that maps human-readable domain names (like google.com) to machine-readable IP addresses.

\* \*\*Public vs. Private IP:\*\* Private IPs operate strictly inside a local area network for secure local device communication. Public IPs are globally unique and face the open internet.



\---



\## 🗺️ Part C: Network Diagram

Below is the architectural diagram mapping out my local station's connectivity pathway:



!\[Network Diagram](./diagrams/network\_diagram.png)



\---



\## ⚡ Part D: Connectivity Tests



\### 📊 Ping Analysis

\* \*\*Status:\*\* Successful connection established.

\* \*\*Results:\*\* 4 Packets Sent, 4 Received, 0% Packet Loss.

\* \*\*Latency Profile:\*\* Minimum = 89ms, Maximum = 115ms, Average = 101ms.



\### 🗺️ Traceroute Analysis

\* \*\*Target Address:\*\* google.com \[`2404:6800:4007:82::200e`]

\* \*\*Total Hops:\*\* 11 intermediate routing hops recorded to complete the trace.

\* \*\*Purpose:\*\* To visualize the routing path and identify transit delays across different network segments.



\---



\## 🖼️ Verification Artifacts

To verify the command metrics listed above, the original command execution outputs have been documented below:



\### Network Configuration Status (`ipconfig /all`)

!\[Network Configuration Status](./screenshots/network\_config.png)



\### Connectivity Diagnostic Checks (`ping` \& `tracert`)

!\[Connectivity Diagnostic Checks](./screenshots/connectivity\_tests.png)



\---



\## 🛠️ Tools Used

\* \*\*Command Line Tools:\*\* `ipconfig /all`, `ping`, `tracert`

\* \*\*Documentation Platform:\*\* Markdown, Git, GitHub

