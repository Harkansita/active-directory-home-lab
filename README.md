# Active Directory Home Lab

## Overview

This project demonstrates the deployment of a complete Windows Server 2025 Active Directory lab using VMware Workstation.

The environment includes a Domain Controller, DNS, DHCP, Group Policy Objects (GPOs), shared folders secured with NTFS permissions, and a Windows 11 Enterprise client joined to the domain.

The objective of this lab was to simulate a small business environment and gain hands-on experience with common Windows Server administration tasks.

---

## Technologies Used

- Windows Server 2025 Standard
- Windows 11 Enterprise
- VMware Workstation
- Active Directory Domain Services (AD DS)
- DNS
- DHCP
- Group Policy (GPO)
- NTFS Permissions
- SMB File Sharing

---

## Lab Architecture

- **Domain:** homelab.local
- **Domain Controller:** DC01
- **Client:** CLIENT01
- **Server IP:** 192.168.215.10
- **Network:** NAT (VMware)

![Network Diagram](Diagram/network-diagram.png)

---

# Deployment Screenshots

## Windows Server Installation

![Windows Server Installation](Screenshots/01-windows-server-installation.png)

---

## Initial Server Configuration

![Local Server](Screenshots/02-local-server-default.png)

![Static IP Configuration](Screenshots/03-static-ip-configuration.png)

---

## Active Directory Installation

![Install AD DS](Screenshots/04-install-adds-features.png)

![Create New Forest](Screenshots/05-create-new-forest.png)

![Domain Controller Options](Screenshots/06-domain-controller-options.png)

![DNS Manager](Screenshots/07-dns-manager.png)

---

## Active Directory Organization

![Organizational Units](Screenshots/08-organizational-units.png)

![Security Groups](Screenshots/09-security-groups.png)

![Domain Users](Screenshots/10-domain-users.png)

---

## File Server

![Department Folders](Screenshots/11-department-folders.png)

![NTFS Permissions](Screenshots/15-ntfs-permissions-denied.png)

---

## DHCP

![DHCP Scope](Screenshots/12-dhcp-scope-active.png)

---

## Client Configuration

![Client Joined Domain](Screenshots/13-client-joined-domain.png)

![Client Receiving DHCP](Screenshots/14-client-receiving-dhcp.png)

---

## Group Policy

![Login Banner](Screenshots/16-login-banner.png)

---

## Skills Demonstrated

- Windows Server Administration
- Active Directory Management
- User and Group Administration
- DNS Configuration
- DHCP Configuration
- Group Policy Management
- NTFS Permission Management
- Troubleshooting
- Windows Client Administration

---

## Project Status

✅ Completed