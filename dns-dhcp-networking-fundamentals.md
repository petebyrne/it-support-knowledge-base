# DNS, DHCP and Networking Fundamentals

## What Is DNS?

DNS translates human-readable names into IP addresses.

Example:

```text
google.com → 142.250.x.x
```

Without DNS, users would need to remember IP addresses instead of website names.

## What Is DHCP?

DHCP automatically assigns network settings to devices when they join a network.

DHCP can provide:

- IP address
- Subnet mask
- Default gateway
- DNS server

## DNS vs DHCP

DNS helps devices find services by name.

DHCP gives devices the network settings they need to communicate.

Example:

1. A laptop connects to Wi-Fi.
2. DHCP assigns it an IP address.
3. DHCP provides a DNS server.
4. DNS translates website names into IP addresses.

## Common Networking Terms

### IP Address

A unique address used to identify a device on a network.

### Default Gateway

The device, usually a router or firewall, that sends traffic outside the local network.

### LAN

Local Area Network.

Example:

- Office network
- Home network

### WAN

Wide Area Network.

Example:

- Internet connection
- Connection between offices

### TCP/IP

The core set of networking protocols used for communication across networks and the internet.

## Common 1st Line Network Checks

### 1. Check Scope

Ask:

- Is one user affected?
- Are multiple users affected?
- Is the whole office affected?

### 2. Check Physical or Wireless Connection

Confirm:

- Ethernet cable connected
- Wi-Fi enabled
- Correct network selected

### 3. Check IP Address

On Windows:

```cmd
ipconfig
```

Look for:

- Valid IPv4 address
- Default gateway
- DNS server

### 4. Test Connectivity

Use:

```cmd
ping
```

Example:

```cmd
ping 8.8.8.8
```

If this works but websites do not, DNS may be the issue.

### 5. Test Name Resolution

Example:

```cmd
ping google.com
```

If pinging an IP works but pinging a name fails, DNS may be failing.

## Interview Questions

### What is DNS?

> DNS translates names such as google.com into IP addresses so devices can find services on a network.

### What is DHCP?

> DHCP automatically assigns IP addresses and network settings to devices when they connect to a network.

### How do DNS and DHCP work together?

> DHCP gives a device its network settings, including which DNS server to use. DNS then translates website or service names into IP addresses.

### A user says the internet is not working. What would you check first?

> I would first determine whether the issue affects one user or multiple users, then check whether the device has a valid network connection, IP address, gateway and DNS settings.

### What might it mean if a device has a 169.254.x.x address?

> It usually means the device has not received a valid IP address from DHCP.

## Interview Summary

A strong 1st line explanation:

> DNS translates names into IP addresses, while DHCP automatically assigns network settings to devices. When troubleshooting network issues, I would check scope, connectivity, IP address, gateway and DNS resolution before escalating if required.
