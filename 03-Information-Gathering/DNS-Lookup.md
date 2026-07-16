# DNS Lookup

## Objective

Find the IP address associated with **google.com** and understand how DNS resolution works.

---

## Command Used

```bash
nslookup google.com
```

---

## Sample Output

```text
Server:         8.8.8.8
Address:        8.8.8.8#53

Non-authoritative answer:
Name:    google.com
Address: 142.250.xxx.xxx
```

---

## Explanation

The `nslookup` command queries a Domain Name System (DNS) server to retrieve information about a domain name.

In this exercise, `nslookup` was used to resolve **google.com** into its corresponding IP address.

### What is DNS Resolution?

DNS (Domain Name System) resolution is the process of converting a human-readable domain name (such as **google.com**) into a machine-readable IP address (such as **142.250.xxx.xxx**).

DNS acts like the **phonebook of the Internet**, allowing users to access websites using names instead of remembering numerical IP addresses.

---

## Why this Command is Useful

- Resolves domain names into IP addresses.
- Verifies DNS server functionality.
- Helps troubleshoot DNS-related problems.
- Identifies the IP address of remote hosts.

---

## Cybersecurity Relevance

DNS lookup is commonly performed during:

- Footprinting
- Open Source Intelligence (OSINT)
- Network Reconnaissance
- Incident Response
- Malware Investigation

Security analysts frequently verify domain names before scanning or investigating external systems.

## Conclusion

The `nslookup` command is a simple but powerful tool for verifying DNS resolution and identifying the IP addresses associated with domain names.
