# Security Hardening

This section documents the security controls applied to the Secure Data Infrastructure Lab.

The objective was to reduce unnecessary exposure, preserve required connectivity, and strengthen remote administration between Ubuntu Server and Windows Server.

## Ubuntu Firewall

Ubuntu Server used UFW as the host-based firewall.

The required services were explicitly allowed:

- TCP port `22` for SSH
- TCP port `8888` for JupyterLab

Firewall status and rules were verified using:

```bash
sudo ufw status numbered
