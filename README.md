# Azure Linux VM Setup with SSH

## 🚀 Overview
This project demonstrates how to create and connect to a Linux Virtual Machine in Microsoft Azure using SSH.

## 🧱 Steps Performed

1. Created Resource Group
2. Created Ubuntu 22.04 VM
3. Generated SSH key (.pem)
4. Opened port 22 (SSH)
5. Connected via PowerShell using SSH
6. Fixed key permission using icacls
7. Verified connection
8. Deallocated VM to control cost

## 🔐 SSH Command Used

```bash
ssh -i DemoKey.pem abhi@<public-ip>
Key Learnings
Difference between Public IP and Private IP
Handling SSH in Windows environment
Azure VM lifecycle (Start/Stop/Deallocate)


(Add your screenshots here)

📌 Tools Used
Microsoft Azure
Ubuntu Linux
PowerShell
