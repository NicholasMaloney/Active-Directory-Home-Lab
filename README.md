## Project Overview

This repository showcases my Active Directory home lab project, where I built a complete security testing environment to explore both defensive measures and offensive techniques. For the full walkthrough with detailed implementation steps and screenshots, visit my personal website where I've documented the entire project. 

## Environment Setup

The lab environment consists of:

- Windows Server 2022 as Domain Controller (DC1)
- Windows 11 management client
- Multiple Windows 11 workstations enrolled in the xyz.local domain

## Key Features

- **User Management Automation**: PowerShell scripts for creating random users and groups with weakened password policies for testing purposes
- **Security Testing Tools**: Implementation of industry-standard penetration testing tools
- **Attack Simulation**: Practical demonstrations of common AD attack vectors

## Security Testing Techniques

This project demonstrates several security techniques including:

- Brute force attacks using CrackMapExec
- Remote shell operations with Impacket
- Domain enumeration using Bloodhound CE
- Local admin account creation automation
- Kerberoasting attacks for obtaining and cracking Kerberos TGS hashes

## Documentation

For comprehensive documentation including step-by-step guides, implementation details, and security findings, please visit [my websit](https://nicholasmaloney.notion.site/Projects-1414fea9b869807aae6ff20bacf02285).
- [Creating An Active Directory Lab](https://nicholasmaloney.notion.site/Active-directory-Lab-3136bc502b21439a855172b1f387e5e7)
- [BruteForcing AD Domain Passwords - CrackMapExec](https://nicholasmaloney.notion.site/Brute-Force-Attack-13c4fea9b869801e85efc6901d70a1fd)
- [Active Directory Domain Enumeration With Bloodhound CE](https://nicholasmaloney.notion.site/Bloodhound-Domain-Enumeration-13d4fea9b869806e9a26de7f2c839bfe)
- [PowerShell - Automating Local Admin Accounts ](https://nicholasmaloney.notion.site/PowerShell-Automating-Local-Admin-Accounts-13e4fea9b8698009a9cdc0611ce0e3fc)
- [Enumerating & Compromising Windows Hosts - CrackMapExec, Impacket & Bloodhound](https://nicholasmaloney.notion.site/Enumerating-Compromising-Windows-Hosts-CrackMapExec-Impacket-Bloodhound-1404fea9b86980cb9d54cef700cb667c)
- [Learning Kerberoasting: Active Directory Exploitation](https://nicholasmaloney.notion.site/Learning-Kerberoasting-Active-Directory-Exploitation-1404fea9b86980c19396f6067590d30c)

## Inspiration

This project was inspired by John Hammond's Active Directory YouTube playlist and extends the concepts with additional security testing scenarios.

## Disclaimer

This project is intended for educational purposes only. The techniques demonstrated should only be performed in controlled lab environments with proper authorization.
