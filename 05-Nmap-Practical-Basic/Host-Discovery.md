# Host Discovery

## Objective

Determine whether a target host is online without performing a complete port scan.

---

## Command Used

```bash
nmap -sn scanme.nmap.org
```

---

## Sample Output

```text
Starting Nmap...

Nmap scan report for scanme.nmap.org

Host is up.
```

---

## Explanation

The `-sn` option performs **Host Discovery**, previously known as a "Ping Scan."

Unlike a normal Nmap scan, this option:

- Checks whether the host is reachable.
- Does not scan ports.
- Completes much faster than a full scan.

This technique is useful when the goal is simply to identify active systems on a network.

---

## Why Host Discovery is Useful

Host discovery helps:

- Identify live hosts.
- Reduce unnecessary port scans.
- Improve scanning efficiency.
- Build an inventory of active devices.

---

## Cybersecurity Relevance

Host discovery is one of the earliest phases of:

- Network Reconnaissance
- Asset Enumeration
- Internal Network Mapping
- Vulnerability Assessments

Security teams often discover all active systems before beginning detailed scans.

## Conclusion

The `nmap -sn` command quickly determines whether a host is online, making it an efficient first step before performing more comprehensive network scans.
