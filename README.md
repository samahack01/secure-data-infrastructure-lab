# Secure Data Infrastructure Lab

Design, deployment, networking, containerization, security hardening, and validation of a cross-platform data infrastructure using Linux, Windows Server, Docker, JupyterLab, and Python.

## Project Overview

This project documents the progressive development of a virtual data infrastructure built throughout an academic operating systems laboratory.

The environment evolved from basic server virtualization and process monitoring into a cross-platform architecture composed of Ubuntu Server and Windows Server nodes, internal networking, routing, access control, containerized services, firewall hardening, and data analytics.

The final environment provides a secured infrastructure capable of running JupyterLab inside Docker while maintaining controlled communication between Linux and Windows systems.

## Architecture

The laboratory environment includes:

- Ubuntu Server as the primary infrastructure and application node
- Windows Server as a secondary processing and administration node
- Oracle VirtualBox for virtualization
- NAT and internal virtual networks
- Linux IP forwarding and NAT routing
- Docker containerization
- JupyterLab as the data science environment
- SSH for remote administration
- UFW and Windows Defender Firewall for host-level security
- Python, Pandas, and Matplotlib for application validation

## Technologies

- Linux / Ubuntu Server
- Windows Server
- PowerShell
- Bash / Linux CLI
- Oracle VirtualBox
- TCP/IP
- NAT
- IP Forwarding
- iptables
- SSH
- Docker
- JupyterLab
- Python
- Pandas
- Matplotlib
- UFW
- Windows Defender Firewall
- NTFS ACLs
- Git / GitHub

## Project Development

### Phase 1 — Virtual Infrastructure
Deployment and administration of Linux and Windows Server virtual machines and comparison of operating system architectures.

### Phase 2 — Process and Resource Management
Monitoring processes and system resources using Linux CLI tools and Windows graphical/command-line utilities.

### Phase 3 — Access Control and Permissions
Implementation and remediation of Linux file permissions and Windows NTFS access control lists.

### Phase 4 — Cross-Platform Networking
Configuration of static addressing, internal networking, connectivity testing, IP forwarding, and NAT routing between Ubuntu and Windows.

### Phase 5 — Identity and Service Management
Management of local users and deployment of containerized services using Docker.

### Phase 6 — Docker and JupyterLab
Deployment of JupyterLab inside a Docker container and remote access from the Windows environment.

### Phase 7 — Security Hardening
Implementation of host-based firewall rules using UFW and Windows Defender Firewall while preserving required SSH, ICMP, and application traffic.

### Phase 8 — Data Analytics Validation
Validation of the secured infrastructure by executing Python workloads using Pandas and Matplotlib inside JupyterLab.

## Skills Demonstrated

- Linux and Windows system administration
- Virtual infrastructure deployment
- Command-line administration
- Network troubleshooting
- Cross-platform networking
- Access control and least privilege
- Container deployment
- Firewall configuration
- SSH administration
- Infrastructure troubleshooting
- Data science environment deployment

## Documentation

Detailed architecture diagrams, configuration procedures, commands, screenshots, and technical evidence will be organized within this repository.

## Status

Portfolio documentation in progress.
