*This project has been created as part of the 42 curriculum by <login>.*

# NetPractice

## Description
NetPractice is a networking project designed to introduce the fundamentals of computer networking and TCP/IP addressing. The objective is to solve 10 simulated network levels by configuring IP addresses, subnet masks, default gateways, and routing tables to establish end-to-end host communication.

## Instructions
- **Run the interface:** Execute `run.sh` from the application directory. The script scans for an available port starting from `49152` (defaulting to `49242` if `ss` is unavailable) and opens `http://localhost:<port>` in your web browser. Alternatively, start a server manually with `python3 -m http.server <port>`.
- **Login:** Enter your 42 login in the training tab to load your assigned network scenarios.
- **Export Configurations:** After successfully completing each level, click the `Get my config` button to download the configuration file for that level.
- **Submission:** Place all 10 exported configuration files (one per level) directly at the root of your Git repository.

## Resources
- **Networking Concepts Studied:**
  - OSI layers
  - TCP/IP addressing
  - Subnet masks
  - Default gateways
  - Routers and switches
  - Network topology
  - Types of area networks (LAN, MAN, WAN)
- **Articles**
  - [OSI Model](https://www.geeksforgeeks.org/computer-networks/open-systems-interconnection-model-osi/)  
  - [TCP/IP Model](https://www.geeksforgeeks.org/computer-networks/tcp-ip-model/)  
  - [Network Devices](https://www.geeksforgeeks.org/computer-networks/network-devices-hub-repeater-bridge-switch-router-gateways/)  
  - [Network Topology](https://www.geeksforgeeks.org/computer-networks/network-topology/)  
  - [Types Of Area Networks](https://www.geeksforgeeks.org/computer-networks/types-of-area-networks-lan-man-and-wan/)
- **Videos**
  - [Network Topology](https://youtu.be/cLuBLwa3XlI?si=--_SPX1-oPEJjxue)
  - [Cast Types](https://youtu.be/GCHcGimdA3g?si=YZqQnz06gkYBgCl7)
  - [OSI Modle](https://youtu.be/61kRxdZ5p-o?si=wbGGSqodcD1ScGTf)
  - [Types Of Area Networks](https://youtu.be/sPevWU0O7bI?si=uXU4eqTGM7Hfl8FJ)
  - [IP Address](https://youtu.be/5WfiTHiU4x8?si=Pn0Bva6ziE_XO8_r)
  - ***Private Public IP Addresses***: [First](https://youtu.be/tcae4TSSMo8?si=U8Q_M4ff5qtn_Yls)&[Second](https://youtu.be/8bhvn9tQk8o?si=3Gvwd-ArcaRwaqCw)
- **AI Usage**
  - Used AI to learn and practice subnetting mechanics, binary conversions, and address calculations.
  - Used AI as a thought partner to consolidate core networking concepts and clarify ambiguous routing scenarios.
  - Used AI to scaffold and format the initial template of this `README.md` file.