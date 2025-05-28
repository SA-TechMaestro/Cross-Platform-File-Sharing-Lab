# 🔗 Cross-Platform File Sharing & Troubleshooting Lab

This entry-level lab explores how to configure file sharing between a Linux (Ubuntu) and two Windows 10 virtual machines. The goal was to set up, secure, and test a Samba file share, and ensure both Windows VMs could access it.

## 🧰 Technologies Used

- Ubuntu Linux (Samba Server)
- Windows 10 Virtual Machines
- nano (text editor)
- Linux/Windows networking tools (ping, SMB)
- VMware

## 📋 Summary of Steps

1. Updated Ubuntu system and installed Samba
2. Backed up the default Samba config file
3. Set up a second Windows 10 VM
4. Created a shared folder on Ubuntu using Samba
5. Updated permissions and Samba configuration using `nano`
6. Allowed Samba traffic through the firewall
7. Confirmed both Windows VMs could access the share via:  
   `\\192.168.80.128\SharedFolder`

## 🔍 Key Concepts Demonstrated

- Cross-platform networking and IP configuration
- SMB (Server Message Block) sharing via Samba
- Linux file permissions and firewall rules
- Windows-to-Linux file sharing over a local network

## 📂 Repo Contents

| File / Folder                            | Description                              |
|------------------------------------------|------------------------------------------|
| `report.md`                              | Detailed walkthrough and findings        |
| `/images/`                               | Screenshots of configuration and results |
| `File-Sharing-Configuration-and-Troubleshooting_Lab.pdf` | Original submitted report (PDF) |

---

✅ This lab helped reinforce basic troubleshooting and system integration practices used in help desk, IT support, and system administration roles.
