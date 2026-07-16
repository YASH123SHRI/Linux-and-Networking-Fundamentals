# MX Records

## Objective

Retrieve the Mail Exchange (MX) records for **google.com** and understand their purpose.

---

## Command Used

```bash
dig google.com MX
```

---

## Sample Output

```text
google.com.      260   IN   MX   10 smtp.google.com.
```

---

## Explanation

The `dig` (Domain Information Groper) command is an advanced DNS lookup utility used to query DNS records.

Compared to `nslookup`, `dig` provides:

- Cleaner output
- Detailed DNS information
- Standardized DNS response format
- Better troubleshooting capabilities

---

## Understanding the Output

Example:

```text
google.com.   260   IN   MX   10 smtp.google.com.
```

| Field | Meaning |
|--------|----------|
| google.com | Queried domain |
| 260 | Time To Live (TTL) in seconds |
| IN | Internet class |
| MX | Mail Exchange record |
| 10 | Mail server priority |
| smtp.google.com | Mail server handling incoming emails |

---

## What are MX Records?

MX (Mail Exchange) records specify which mail servers are responsible for receiving emails for a domain.

Whenever someone sends an email to:

```text
user@example.com
```

the sender's mail server checks the domain's MX records to determine where the email should be delivered.

Without MX records, email delivery would not be possible.

---

## Cybersecurity Relevance

MX records are valuable during:

- Email infrastructure reconnaissance
- Security assessments
- Phishing investigations
- Email security audits
- OSINT

Attackers and defenders both analyze MX records to understand an organization's email infrastructure.

## Conclusion

The `dig` command provides detailed DNS information, while MX records identify the mail servers responsible for receiving email on behalf of a domain.
