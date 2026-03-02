# Snort-IDS-IPS-Lab
Implemented a virtual IDS/IPS security lab using pfSense and Snort to detect, monitor, and block real-time attack simulations.
# Intrusion Detection & Prevention Lab using Snort on pfSense

## 📌 Project Overview
This project demonstrates the implementation of an IDS/IPS lab using:
- pfSense Firewall
- Snort IDS/IPS
- Kali Linux (Attacker)
- Ubuntu Server (Victim)

## 🏗 Architecture

Kali (192.168.100.x)
↓
VMnet7 (WAN)
↓
pfSense (WAN: 192.168.100.1 | LAN: 172.16.0.1)
↓
VMnet8 (LAN)
↓
Ubuntu (172.16.0.50)

## 🔍 Features
- Port scan detection using Snort
- Automatic IP blocking (IPS mode)
- Rule-based intrusion detection
- Firewall traffic inspection

## 🧪 Testing
- Nmap SYN Scan
- Snort Alerts verification
- Blocked Hosts verification

## 🎯 Result
Snort successfully detected and blocked malicious scanning activity.
