# Network Interfaces

## Objective

Display all network interfaces and identify the active interface used for network communication.

---

## Commands Used

Display routing table:

```bash
ip r
```

Display all network interfaces:

```bash
ip a
```

---

## Explanation

### ip a

The `ip a` command displays all network interfaces available on the system, including:

- Interface names
- MAC addresses
- IPv4 and IPv6 addresses
- Interface status (UP/DOWN)

This command helps identify which interfaces are currently active.

---

### ip r

The `ip r` command displays the system's routing table.

It shows:

- Default gateway
- Network routes
- Destination networks
- Packet forwarding paths

The routing table determines how outgoing network traffic reaches its destination.

---

## Difference Between ip a and ip r

| ip a | ip r |
|------|------|
| Shows network interfaces | Shows routing table |
| Displays assigned IP addresses | Displays packet routes |
| Identifies active interfaces | Identifies default gateway |
| Used for interface configuration | Used for network routing |

In simple terms:

> **`ip a` tells you who you are on the network, while `ip r` tells you where your traffic is going.**

---

## Cybersecurity Relevance

These commands are frequently used during:

- Network reconnaissance
- Incident response
- Firewall troubleshooting
- Network diagnostics
- SOC investigations
- Penetration testing

Understanding network interfaces and routing is essential before conducting vulnerability assessments or packet analysis.

## Conclusion

The `ip a` and `ip r` commands provide complete visibility into the system's network configuration and routing information, making them indispensable tools for Linux administration and cybersecurity professionals.
