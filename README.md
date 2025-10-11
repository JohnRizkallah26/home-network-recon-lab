# 🧪 Home Network Recon Lab

## 🎯 Objective
This lab demonstrates tactical network reconnaissance using Kali Linux in VirtualBox to scan and document a live home network. The goal is to identify active hosts, open ports, and service fingerprints using Netdiscover and Nmap, then annotate findings for portfolio and SOC readiness.

---

## 🛠️ Lab Setup

- **Attacker VM:** Kali Linux (Bridged Adapter)
- **Target Environment:** Home LAN (192.168.68.0/24)
- **Tools Used:**
  - `netdiscover` – ARP-based host discovery
  - `nmap` – Port scanning and service enumeration
  - `ip a`, `ip route` – Interface and subnet verification
  - `scrot` – Screenshot capture for documentation

---

## 🔍 Recon Workflow

### 1. Identify Subnet
```bash
ip a
ip route
