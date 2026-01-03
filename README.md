# ubuntu-security-audit
Overview
This project demonstrates a full security audit and hardening of an Ubuntu 24.04 server running in a virtualized environment.  
The objective was to identify insecure configurations and apply industry-standard Linux security best practices.

## 🧑‍💻 Role
Junior Linux Security Administrator (Lab Simulation)

## 🖥️ Environment
- Ubuntu 24.04
- Oracle VirtualBox
- Bash
- UFW Firewall

## 🎯 Objectives
- Configure secure user roles (standard & super user)
- Automate user creation using Bash
- Demonstrate insecure login practices (controlled lab)
- Secure the system using UFW
- Apply system hardening measures
- Document findings and remediation

## 🛠️ Tools Used
- Bash
- sudo
- adduser / usermod
- ufw
- apt

## 🔍 Key Tasks & Evidence

### User & Privilege Management
- Created standard and sudo users
- Enforced least privilege principle

### Firewall Configuration
- Default deny incoming traffic
- Allowed essential services only

### System Hardening
- Disabled root login
- Applied system updates
- Removed unnecessary packages

## 📊 Findings & Mitigations
| Risk | Mitigation |
|-----|------------|
| Excess sudo access | Role separation |
| Open network ports | UFW firewall |
| Unpatched system | Regular updates |

## 📄 Conclusion
The audit significantly improved system security by enforcing least privilege, reducing attack surface, and applying defense-in-depth principles.

## 🚀 Skills Demonstrated
- Linux Security
- Ubuntu Hardening
- Bash Scripting
- Firewall Configuration
- Security Auditing
