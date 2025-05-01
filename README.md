# End-to-End-Secure-Linux-Network-Infrastructure

A hands-on project simulating the complete network infrastructure of a startup using Linux-based systems. Built as part of a Data Networking and Systems Administration course, this project demonstrates practical expertise in configuring and securing essential network services from the ground up.

📌 Project Overview
This project showcases the design and implementation of a secure, scalable, and fully functional enterprise network environment using open-source tools and Linux distributions. It integrates core networking services, automation, security measures, and testing procedures.

⚙️ Technical Highlights
1. 🔁 DNS Implementation
- Configured Bind9 as both Master and Slave DNS servers.
- Enabled domain name resolution for IPv4 and IPv6.
- Included reverse DNS configuration using in-addr.arpa and ipv6.arpa zones.

2. 📡 DHCP Setup
- Deployed a DHCP server to dynamically assign both IPv4 and IPv6 addresses.
- Defined:
  - Address pools
  - Reservation rules
  - Exclusion ranges
- Improved IP management and tracking within the network.

3. 🌐 Web Server Deployment & Firewall Hardening
- Deployed an Apache2 web server accessible over the local network.
- Implemented firewall rules using iptables and ufw:
  - Restricted access by IP and protocol
  - Minimized attack surface
  - Enhanced network perimeter security

4. 💾 Automated Backup System
- Created custom bash scripts to:
  - Perform daily backups
  - Compress data
  - Securely transfer files to a remote backup server using SCP
- Ensured data resilience and disaster recovery readiness.

5. 🔐 VPN Configuration
- Used StrongSwan to set up an IPSec VPN tunnel between two Linux machines.
- Facilitated encrypted communication for secure remote access.

6. 📁 File Sharing Infrastructure
- Set up NFS (Network File System) for cross-machine file sharing within the LAN.
- Enabled collaboration and resource accessibility across departments.

7. 🛡️ Security Testing - ARP Poisoning Simulation
- Simulated ARP spoofing attacks using Scapy for:
  - Evaluating LAN vulnerabilities
  - Validating firewall rules and defensive setups

📚 Skills Gained
- Linux System Administration
- Network Services Deployment (DNS, DHCP, NFS, Web Server)
- Firewall Configuration and Intrusion Mitigation
- Bash Scripting for Automation
- VPN and Encrypted Communication Setup
- Network Security Testing

🧪 Future Enhancements
- Implement centralized logging and monitoring with tools like Syslog, Nagios, or Zabbix.
- Add LDAP for centralized authentication and user management.
- Extend the architecture to support high availability with load balancers and redundancy.

🛠️ Tools & Technologies

Category	         :         Tools/Technologies

OS	               :         Ubuntu Server
DNS	               :         Bind9
DHCP	             :         isc-dhcp-server
Web Server	       :         Apache2
VPN	               :         StrongSwan
Backup & Transfer	 :         Bash, SCP
File Sharing	     :         NFS
Firewall	         :         iptables, ufw
Security Testing	 :         Scapy

📎 License
This project is for educational purposes only. No license is attached.
