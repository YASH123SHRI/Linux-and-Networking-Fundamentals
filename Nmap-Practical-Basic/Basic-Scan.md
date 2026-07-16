# Nmap Basic Scan

## Objective

Perform a basic Nmap scan on a target host to identify reachable systems and discover open TCP ports.

---

## Command Used

```bash
nmap scanme.nmap.org
```

---

## Sample Output

```text
Starting Nmap...

Nmap scan report for scanme.nmap.org

PORT     STATE SERVICE
22/tcp   open  ssh
80/tcp   open  http
```

---

## Explanation

Nmap (Network Mapper) is an open-source network scanning tool used to discover hosts and services on a network.

Running a basic scan without additional options causes Nmap to:

- Check whether the target host is reachable.
- Scan the 1,000 most common TCP ports.
- Report the state of each discovered port.
- Identify common services running on open ports.

---

## Understanding the Output

| Field | Description |
|--------|-------------|
| PORT | Port number being scanned |
| STATE | Current status (Open, Closed, Filtered) |
| SERVICE | Common service associated with the port |

Example:

- **22/tcp** → SSH service
- **80/tcp** → HTTP web server

---

## Why this Scan is Useful

A basic scan helps security professionals:

- Verify host availability.
- Identify exposed services.
- Detect unnecessary open ports.
- Begin network reconnaissance.

---

## Cybersecurity Relevance

Basic port scanning is usually the first step during:

- Vulnerability Assessment
- Penetration Testing
- Network Auditing
- Asset Discovery
- SOC Investigations

Understanding exposed services helps determine the potential attack surface.

## Conclusion

A basic Nmap scan provides a quick overview of the target system by identifying reachable hosts and commonly exposed TCP services.
