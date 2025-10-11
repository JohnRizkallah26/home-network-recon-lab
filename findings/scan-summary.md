# 🧾 Scan Summary – Johns Key West Home Network Recon Lab 🌴

## 🔍 Subnet Scanned
- Range: `192.168.68.0/24`
- Scanner IP: `192.168.68.111`
- Gateway: `192.168.68.1`

---

## 📡 Netdiscover Results

| IP Address       | MAC Address         | Vendor                          | Count |
|------------------|---------------------|---------------------------------|-------|
| 192.168.68.1     | 00:1A:2B:XX:XX:XX   | TP-Link Technologies Co          | 146   |
| 192.168.68.109   | 00:1C:3D:YY:YY:YY   | Unknown Vendor                  | 8     |
| 192.168.68.101   | 08:00:27:ZZ:ZZ:ZZ   | Binatone Electronics            | 1     |

📸 Screenshot: `screenshots/netdiscover.png`

---

## 🔬 Nmap Results

### Host: `192.168.68.1` (Router)
```text
Open Ports:
- 80/tcp (HTTP)
- 443/tcp (HTTPS)
- 53/tcp (Domain)
OS Guess: Linux 2.6.32 - 3.10
