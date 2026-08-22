# Networking

This section documents the internal network configuration, routing, NAT, and connectivity validation used in the Secure Data Infrastructure Lab.

The objective was to establish communication between Ubuntu Server and Windows Server while allowing the Windows node to reach external networks through Ubuntu.

## Network Design

The internal network uses the following addressing scheme:

- Ubuntu Server: `192.168.50.1`
- Windows Server: `192.168.50.2`
- Network: `192.168.50.0/24`

Ubuntu Server acts as the routing node between the internal network and the NAT-enabled interface.

## Ubuntu Routing and NAT

IP forwarding was enabled on Ubuntu Server using:

```bash
sudo sysctl -w net.ipv4.ip_forward=1
