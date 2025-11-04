# 🛡️ Task 8 – VPN Setup and Privacy Report

## 🎯 Objective
To gain hands-on experience with Virtual Private Networks (VPNs) and understand how they protect online privacy, secure data transmission, and anonymize user identity.

---

## 🧰 Tools & Resources
- **VPN Client:** ProtonVPN (Free Tier)  
- **Verification Site:** [https://whatismyipaddress.com](https://whatismyipaddress.com)  
- **Protocol Used:** WireGuard (UDP)  
- **Operating System:** Windows 11  

---

## ⚙️ Steps Performed

1. **Checked the original IP address** before connecting to the VPN.  
   - Verified location: *Chennai, India*  
   - (Screenshot: `before-vpn-safe.png`)

2. **Connected to ProtonVPN (Free Japan Server)**  
   - Server: `JP-FREE#20`  
   - Verified new IP and location using *WhatIsMyIPAddress* website.  
   - (Screenshot: `vpn-connected.png`)

3. **Tested secure browsing** by accessing multiple websites and confirming encrypted HTTPS connection.

4. **Disconnected from the VPN** and confirmed that the IP reverted to the original Indian IP.  
   - (Screenshot: `after-vpn-safe.png`)

---

## 📊 Observations

| State              | IP Address (Hidden) | Location        | Notes |
|--------------------|--------------------|-----------------|-------|
| Before VPN         | [Hidden for Privacy] | Chennai, India  | Real IP address before VPN |
| While Connected    | 212.102.51.38       | Tokyo, Japan    | VPN successfully masked IP |
| After Disconnecting| [Hidden for Privacy] | Chennai, India  | IP restored to normal |

---

## 🔐 VPN Features Observed
- **Encryption:** AES-256-bit (industry standard)  
- **Protocol:** WireGuard (UDP)  
- **Extra Features:** Kill Switch, Split Tunneling, NetShield  
- **Connection Type:** Encrypted tunnel between user and VPN server  

---

## 🧠 Understanding VPNs

A **Virtual Private Network (VPN)** encrypts all internet traffic between a device and the VPN server.  
It hides the user's real IP address, ensuring online privacy, security on public Wi-Fi, and bypassing regional restrictions.

### Common VPN Protocols
- **OpenVPN:** Reliable, secure, open-source protocol.  
- **WireGuard:** Modern, lightweight, and fast.  
- **IKEv2/IPSec:** Stable on mobile devices and networks with frequent drops.

---

## ⚖️ Advantages vs Limitations

### ✅ Benefits
- Masks IP address and hides user identity  
- Encrypts online traffic (protection on public Wi-Fi)  
- Helps bypass regional restrictions  
- Prevents ISP tracking  

### ⚠️ Limitations
- Slightly reduced internet speed due to encryption overhead  
- Free versions may offer limited server locations  
- VPNs do **not** provide complete anonymity (provider logs, browser tracking, etc.)

---

## 🧾 Conclusion
Using **ProtonVPN**, the connection was securely established to a Japan-based server, successfully masking my original IP and encrypting my browsing traffic.  
This practical task demonstrates how VPNs protect user privacy, though performance may vary with free plans.

---

## 📸 Screenshots
| Screenshot | Description |
|-------------|--------------|
| `before-vpn-safe.png` | Real IP address (hidden for privacy) |
| `vpn-connected.png` | VPN connection established – IP changed to Japan |
| `after-vpn-safe.png` | Disconnected – IP restored to India |

---

## 🧩 Key Concepts
**VPN, Encryption, Privacy, WireGuard Protocol, Network Security**

---
### **Author**
- **Cybersecurity Intern – Task 8** 
- Your Name : DHANUSH S 
- Date: 31 Oct 2025

