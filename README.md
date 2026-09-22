🛰️ Network Scanning with Zenmap

A hands-on cybersecurity lab exploring **network discovery and host enumeration** using **Zenmap**, the official GUI front-end for **Nmap**. This project documents the process of identifying live hosts on a local subnet, extracting their IP/MAC addresses, and visualizing the network topology.

---

## 📖 Overview

**Zenmap** is a free, open-source, multi-platform GUI for Nmap, widely used by cybersecurity professionals and penetration testers for network scanning and reconnaissance. This project walks through a complete ping-scan workflow — from installation to topology export — as part of an Ethical Hacking coursework module.

---

## 🎯 Objectives

- Install and configure Zenmap on a Windows host
- Identify the local IP address and LAN subnet
- Perform a **Ping Scan** to discover live hosts on the subnet
- Enumerate IP and MAC addresses of all live hosts
- Visualize and export the network topology as a PDF

---

## 🧰 Tools Used

| Tool | Purpose |
|------|---------|
| **Zenmap** | GUI for running and visualizing Nmap scans |
| **Nmap** | Underlying network scanning engine |
| **CMD (`ipconfig`)** | Identifying local IP address and subnet mask |

---

## 🗂️ Methodology

1. **Install Zenmap** from the [official Nmap site](https://nmap.org/download.html)
2. **Find local IP & subnet** via `ipconfig` in Command Prompt
3. **Run a Ping Scan** (`nmap -sn <subnet>/24`) in Zenmap to detect live hosts
4. **Review the Nmap Output** tab for host status, latency, and MAC vendor info
5. **Switch to the Topology tab**, enable the legend, and export the graphic as a **PDF**

---

## 📊 Sample Results
![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)


**Live hosts found:** 

![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%202.png)



---
## 🖼️ Network Topology

The Zenmap **Topology** tab generates a visual map of discovered hosts relative to `localhost`, with color-coded nodes indicating open-port counts and connection types. The final topology was exported as a PDF for inclusion in the project report.

![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP3.png)
---


---

## 🔑 Key Takeaways

- **Ping scans (`-sn`)** are a fast, non-intrusive way to enumerate live hosts without port scanning
- MAC address vendor prefixes (e.g., VMware OUIs) can reveal virtualization or hardware details
- Visualizing topology helps map network structure before deeper enumeration or vulnerability scanning

---

## 📚 References

- [Nmap Official Site](https://nmap.org/)
- [Nmap Reference Guide](https://nmap.org/book/man.html)


This project was conducted in a **controlled, authorized lab environment** for educational purposes only. Always obtain explicit permission before scanning any network you do not own or have authorization to test.

---

# 👤 Author


**KANISHKA M** Cybersecurity Intern B083

LinkedIn: [https://www.linkedin.com/in/kanishka-m525](https://www.linkedin.com/in/kanishka-m525)



