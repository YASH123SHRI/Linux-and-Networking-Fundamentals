# Service Version Detection

## Objective

Identify the software versions running on open ports using Nmap service detection.

---

## Command Used

```bash
nmap -sV scanme.nmap.org
```

---

## Sample Output

```text
PORT     STATE SERVICE VERSION

22/tcp   open  ssh   OpenSSH 6.x

80/tcp   open  http  Apache httpd
```

---

## Explanation

The `-sV` option enables **Service Version Detection**.

Instead of only identifying that a service is running, Nmap attempts to determine:

- Software name
- Software version
- Service banner
- Additional protocol information

This provides much more detailed information than a standard port scan.

---

## Why Version Detection is Important

Knowing software versions allows analysts to:

- Search for known vulnerabilities.
- Compare installed versions against security advisories.
- Verify software updates.
- Detect outdated services.

---

## Cybersecurity Relevance

Service version detection is widely used during:

- Vulnerability Assessments
- Penetration Testing
- Risk Analysis
- Threat Hunting

Many public vulnerabilities (CVEs) affect only specific software versions, making version detection essential before vulnerability analysis.

## Conclusion

Using `nmap -sV` provides detailed service information that helps security professionals identify outdated software and assess potential vulnerabilities.
