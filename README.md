Windows Server 2016 – Final Project

📘 Project Overview

This project was completed as part of the Cybersecurity & Ethical Hacking program at HackerU. The objective was to demonstrate virtualization and Windows domain administration skills by creating a complete environment using Oracle VirtualBox and multiple virtual machines.

Note: All configurations were performed using graphical interface tools (GUI). PowerShell was not used in this project.

🎯 Objectives

Configure and deploy virtual machines (Windows 10, Windows Server 2016, Kali Linux)

Establish a NAT-based internal network for VM communication

Install and promote Windows Server to a Domain Controller

Create Organizational Units (OUs), user accounts, and security groups

Apply Group Policy Objects (GPOs) to enforce restrictions and settings

Create and manage a shared folder with department-based access control

🛠️ Tools & Environments

Oracle VirtualBox

Windows Server 2016 ISO

Windows 10 ISO

Kali Linux OVA

Internal NAT Network: 10.0.2.0/24

✅ Key Tasks Performed

Installed and configured three virtual machines (Windows 10, Windows Server 2016, Kali Linux)

Created a custom NAT network named Virtualization with DHCP support

Verified network connectivity using ping to Google's DNS (8.8.8.8)

Renamed hosts to Server20 and PC1 and joined the domain

Promoted the server to a Domain Controller with Active Directory services

Created five departments (OUs): Developers, IT, QA, HR, and Designers

Created five user accounts per department and assigned them to relevant groups

Configured and deployed GPOs to:

Set department-specific desktop wallpapers

Block Control Panel access for QA

Disable Command Prompt for HR

Implemented an account lockout policy after 3 failed login attempts

Created a shared folder accessible only to Designers and Developers groups

📄 Attached Documentation

The full documentation of all tasks and configurations is provided in the following PDF file:

➡️ [Windows server-2016 final project.pdf](https://github.com/user-attachments/files/21098993/Windows.server-2016.final.project.pdf)


This file includes task breakdowns (Tasks 1–16), screenshots, and configuration steps.

📌 Notes

All tasks were performed via GUI (no scripting or PowerShell involved)

Kali Linux was used strictly for connectivity validation

Resource allocation was optimized for performance in a limited virtualized environment

