# Open Ports Identification

## Objective

Identify the open ports on a target system and understand the services associated with those ports.

---

## Command Used

```bash
nmap scanme.nmap.org
```

---

## Sample Output

```text
PORT     STATE SERVICE
22/tcp   open  ssh
80/tcp   open  http
```

---

## Explanation

An **open port** is a communication endpoint that is actively accepting incoming connections.

Each open port is generally associated with a network service.

Common examples include:

| Port | Service |
|------|----------|
| 22 | SSH |
| 80 | HTTP |
| 443 | HTTPS |
| 21 | FTP |
| 25 | SMTP |

---

## Why Open Ports Matter

Open ports indicate services that are available over the network.

While necessary for legitimate communication, unnecessary open ports may increase the attack surface and become potential entry points for attackers.

---

## Cybersecurity Relevance

Identifying open ports helps security professionals:

- Discover exposed services.
- Detect unnecessary network exposure.
- Prioritize vulnerability assessments.
- Verify firewall configurations.

Port enumeration is a core activity during network reconnaissance.

## Conclusion

Open port identification helps analysts understand which services are accessible on a target system and forms the basis for further security testing.
