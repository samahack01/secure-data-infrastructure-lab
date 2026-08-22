# Architecture

![Secure Data Infrastructure Architecture](architecture-secure-data-infrastructure.png)

This section documents the logical architecture of the Secure Data Infrastructure Lab.

The environment was built using Oracle VirtualBox with two server nodes:

- Ubuntu Server
- Windows Server

Ubuntu Server acts as the primary infrastructure node and provides routing, NAT, SSH access, Docker services, JupyterLab, and host-based firewall protection.

Windows Server acts as the secondary node and is used for connectivity testing, administration, PowerShell-based configuration, firewall validation, and remote access to JupyterLab.

## Logical Topology

```text
Internet
   |
   v
VirtualBox NAT Network
   |
   v
Ubuntu Server
192.168.50.1
   |
   +-- IP Forwarding
   +-- NAT / iptables MASQUERADE
   +-- UFW Firewall
   +-- SSH Service
   +-- Docker
   |     |
   |     └── JupyterLab
   |          Port 8888
   |
   v
Internal Network
   |
   v
Windows Server
192.168.50.2
   |
   +-- Windows Defender Firewall
   +-- PowerShell Administration
   +-- ICMP / Ping Validation
   +-- SSH Client
   +-- Browser Access to JupyterLab
