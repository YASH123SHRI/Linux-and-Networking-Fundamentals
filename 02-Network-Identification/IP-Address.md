# IP Address Identification

## Objective

Identify the IP address assigned to the Linux system and determine whether it is a public or private IP address.

---

## Command Used

```bash
hostname -I
```

---

## Sample Output

```text
10.0.2.15
```

---

## Explanation

The `hostname -I` command displays the IP address currently assigned to the system.

In this lab environment, the returned address belongs to the **10.0.0.0/8** private IPv4 address range, which means it is a **private IP address**. Private IP addresses are used within local networks and cannot be accessed directly from the public internet.

### Private IPv4 Address Ranges

| Range | Purpose |
|--------|----------|
| 10.0.0.0 – 10.255.255.255 | Large private networks |
| 172.16.0.0 – 172.31.255.255 | Medium-sized private networks |
| 192.168.0.0 – 192.168.255.255 | Home and small office networks |

Any IPv4 address outside these reserved ranges is generally considered a public IP address.

---

## Why this Command is Useful

- Displays the current IP address of the system.
- Helps verify network connectivity.
- Assists in troubleshooting network issues.
- Useful before performing network scans or remote connections.

---

## Cybersecurity Relevance

Knowing a system's IP address is one of the first steps during:

- Network reconnaissance
- Vulnerability assessments
- Host identification
- Incident response
- Network troubleshooting

Attackers and defenders both rely on accurate IP identification during security assessments.

## Conclusion

The `hostname -I` command quickly identifies the machine's IP address, allowing security professionals to understand the system's position within the network before beginning any assessment.
