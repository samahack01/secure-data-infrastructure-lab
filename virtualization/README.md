# Virtualization

This section documents the virtualization layer used to build the Secure Data Infrastructure Lab.

The environment was deployed using Oracle VirtualBox as a Type 2 hypervisor running two virtual server nodes:

- Ubuntu Server
- Windows Server

These virtual machines were used to simulate a small cross-platform infrastructure environment in which networking, process management, access control, containerization, firewall configuration, SSH administration, and data analytics could be tested.

## Virtual Machines

### Ubuntu Server

Ubuntu Server was used as the primary infrastructure node.

Its responsibilities included:

- Linux command-line administration
- Internal network configuration
- IP forwarding
- NAT routing
- Docker container hosting
- JupyterLab deployment
- SSH services
- UFW firewall configuration

### Windows Server

Windows Server was used as the secondary node.

Its responsibilities included:

- PowerShell administration
- Windows process management
- Network connectivity validation
- Windows Defender Firewall configuration
- SSH client operations
- Browser access to JupyterLab

## Hypervisor

Oracle VirtualBox provided the virtualization layer used to host and isolate both server operating systems.

The virtual environment allowed the project to reproduce a multi-node infrastructure without requiring separate physical servers.

## Evidence

The following image confirms Windows Server running as a virtual machine inside Oracle VirtualBox:

![Windows Server running in VirtualBox](../evidence/virtualization-windows-server-virtualbox.png)
