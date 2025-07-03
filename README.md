#  Task 4 – Setup and Use a Firewall

##  Objective:
To configure and test basic firewall rules using **Windows Firewall** to allow or block traffic on specific ports.

##  OS Used:
Windows 10  
Firewall: Windows Defender Firewall with Advanced Security  
Testing tool: Telnet

---

##  Steps Followed:

### 1. Enabled Windows Firewall
- Opened `wf.msc` to access advanced firewall settings.

### 2. Blocked Port 23 (Telnet)
- Created a new inbound rule in Windows Firewall to block TCP on port 23.
- Named the rule: `Block Telnet Port 23`.

### 3. Enabled Telnet
- Opened "Turn Windows Features On or Off"
- Enabled **Telnet Client**

### 4. Tested the Rule
```cmd
telnet localhost 23
