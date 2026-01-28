# 🛡 Build Your Personal Cybersecurity Lab – Task 2

## 📌 Overview

This repository documents the implementation of a personal cybersecurity practice lab created as part of a Cybersecurity Internship Program.

The lab provides a safe and isolated penetration-testing environment using virtualization.

---

## 🎯 Objective

To build an isolated cybersecurity lab for practicing:

- Vulnerability Assessment  
- Web Application Testing  
- Network Scanning  
- Security Tool Usage  

---

## 🏗 Lab Architecture

- Attacker Machine: Kali Linux  
- Target Machine: DVWA / OWASP Juice Shop  
- Networking:
  - Adapter 1: NAT (Internet access)
  - Adapter 2: Host-Only (Isolated lab network)

---

## ⚙ Prerequisites

| Requirement | Recommendation |
|------------|---------------|
| RAM | Minimum 8GB |
| Disk | 40–60GB |
| CPU | Virtualization Enabled |
| OS | Windows / Linux / Mac |

---

## 🧰 Tools Used

- Oracle VirtualBox  
- Kali Linux  
- DVWA / OWASP Juice Shop  
- Nmap  
- Burp Suite  
- Wireshark  

---

## 🌐 Network Configuration

Two adapters were configured on Kali Linux:

1. NAT – Internet access  
2. Host-Only – Private sandbox network

This ensures complete isolation from real systems.

---

## 🛠 Implementation Steps

1. Installed VirtualBox and configured Host-Only network  
2. Imported Kali Linux VM  
3. Assigned CPU & RAM  
4. Deployed DVWA target  
5. Verified IP connectivity  
6. Performed ping and Nmap scans  
7. Tested Burp Suite interception  
8. Captured traffic using Wireshark  

---

## ✅ Validation

- Ping Test  
- Nmap Scan  
- Burp Suite Proxy  
- Wireshark Packet Capture  

Screenshots available in `/screenshots`

---

## 📚 Learning Outcomes

- Virtual machine deployment  
- Network segmentation (NAT vs Host-Only)  
- Vulnerable app setup  
- Basic reconnaissance  
- Ethical hacking environment design  

---

## 🏁 Conclusion

A fully isolated cybersecurity lab was successfully implemented. This environment provides a strong foundation for penetration testing practice without risking production systems.

---

## 👤 Author

**Gajendrasinh V. Zala**

Cybersecurity Internship Program – January 2026

---

## 📎 References

- VirtualBox  
- Kali Linux  
- OWASP Juice Shop  
- DVWA  
- Burp Suite  
- Wireshark  
