# WHOIS Lookup

## Objective

Perform a WHOIS lookup on **github.com** and identify publicly available domain registration information.

---

## Command Used

```bash
whois github.com
```

---

## Sample Output

```text
Domain Name: github.com
Registrar: MarkMonitor Inc.
Creation Date: xxxx-xx-xx
Registry Expiry Date: xxxx-xx-xx
Name Servers:
    ns-xxx.awsdns-xx.com
    ns-xxx.awsdns-xx.net
```

---

## Explanation

The `whois` command retrieves publicly available registration details for a domain name or IP address.

WHOIS databases maintain ownership and registration information submitted during domain registration.

---

## Information Provided by WHOIS

A WHOIS lookup typically returns:

- Domain name
- Registrar
- Registration date
- Expiry date
- Last updated date
- Domain status
- Name servers
- Registrant or organization details (when publicly available)
- Administrative and technical contact information

---

## Why this Command is Useful

- Identifies domain ownership.
- Determines domain registration history.
- Finds authoritative name servers.
- Supports infrastructure investigations.
- Assists in verifying domain legitimacy.

---

## Cybersecurity Relevance

WHOIS is widely used during:

- Footprinting
- Open Source Intelligence (OSINT)
- Threat Intelligence
- Phishing Investigations
- Incident Response
- Infrastructure Mapping

It helps analysts identify domain ownership, hosting information, and infrastructure associated with a target organization.

## Conclusion

The `whois` command is an essential reconnaissance tool that provides valuable information about domain ownership, registration details, and DNS infrastructure, making it a key component of cybersecurity investigations.
