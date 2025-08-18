# HONEYPOT

## Objective
Deployed a Cowrie honeypot on a cloud VPS to capture and analyze automated SSH and Telnet attacks, focusing on attacker TTPs and captured malware payloads.

### Skills Learned

- Cloud VPS Deployment & Hardening

- Cowrie Honeypot Installation & Configuration

- Network Traffic Redirection with iptables

- Real-time Log Monitoring & Session Playback Analysis

- Basic Malware Triage (strings)

- Attacker IP Geolocation

### Tools Used

- Honeypot: Cowrie

- Infrastructure: Linux (Ubuntu), Cloud VPS

- Networking: iptables, SSH

- Analysis: Bash, Git, Python, strings, playlog

## Steps

<img width="423" height="87" alt="Lionde VPS configuration settings" src="https://github.com/user-attachments/assets/8f067471-4a12-414c-9a9a-ff4c4640b2a1" />

*Ref 1: Linode VPS Configuration Settings*


<img width="509" height="73" alt="Verifying correct port" src="https://github.com/user-attachments/assets/0d45c122-8803-4135-95df-0b5ec67b981c" />

Ref 2: Changed & verified new SSH port*


<img width="1251" height="21" alt="install py dependencies" src="https://github.com/user-attachments/assets/e0b62710-3618-4d1b-bb21-51d45249568c" />

*Ref 3: Added & installed Python dependencies*


<img width="354" height="201" alt="Add user" src="https://github.com/user-attachments/assets/b56363dd-629f-4789-8465-34fe27631434" />

*Ref 4: Creating new user*


<img width="375" height="18" alt="clonegit" src="https://github.com/user-attachments/assets/53309bbb-bc24-43ff-ad50-e1194be28a1f" />

*Ref 5: Cloning the Cowrie GitHub repository*


<img width="274" height="40" alt="telnetenabled" src="https://github.com/user-attachments/assets/8ac5359f-3473-4a78-a3f4-02874cadb660" />

*Ref 6: Enabling Telnet*


<img width="261" height="15" alt="cowriestart" src="https://github.com/user-attachments/assets/49245048-897b-4f6a-bc0f-7bae1bbd8939" />

*Ref 7: Starting Cowrie*


<img width="1006" height="191" alt="cowrielogs" src="https://github.com/user-attachments/assets/94f42189-d768-4b80-8581-15080b374c18" />

*Ref 8: Cowrie Logs Live*


<img width="903" height="178" alt="malwareanalysis1" src="https://github.com/user-attachments/assets/43749949-fe8d-4858-9fa1-7f657ef0bb26" /><img width="1410" height="87" alt="examineconnections" src="https://github.com/user-attachments/assets/12d68a56-b87c-497b-98ef-1e06a7196492" />

*Ref 9 & 10: Viewing recorded attacker sessions after a few days and Malware analysis with `strings` commands*


<img width="1410" height="87" alt="examineconnections" src="https://github.com/user-attachments/assets/e2eda244-d778-492b-8b20-745ede0cd845" />

*Ref 11: Examining connection logs for attacker IPs and commands*
