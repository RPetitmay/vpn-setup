<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Virtual Private Network Setup and Usage Within An Azure Virtual Machine</h1>
This tutorial outlines the installation, setup and usage of the vpn software Proton VPN. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop (RDC/Windows App)
- Various Command-Line Tools
- Various Network Protocols (SSH, RDP, DNS, HTTP/S, ICMP)
- <a href="https://www.wireshark.org/">Wireshark</a> (Protocol Analyzer)
- Notepad/Notes App (Needed for saving usernames and passwords)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>List of Prerequisites</h2>

- Basic/General Understanding of Microsoft Azure
- Azure Subscription/Azure Account(Portal) created
- Resource Group created within your Azure portal
- Windows 10 Virtual Machine(Windows) created within your Azure portal with the resource group you've created previously
- Linux Virtual Machine(Ubuntu) created within your Azure portal within the resource group <strong>*When creating the linux VM(Ubuntu),under the Networking tab,  make sure to select the same Virtual Network as the one you used for the Windows VM(windows-vm-vnet). If it doesn't appear as an option to be selected, refresh page*</strong>
