# Google Dorking – PDF Search

## Objective

Use Google Dorking to locate publicly available cybersecurity PDF documents from trusted government websites.

---

## Google Dork Used

```text
site:.gov cybersecurity filetype:pdf
```

---

## Explanation of Search Operators

### `site:.gov`

Limits search results to websites using the **.gov** top-level domain.

This ensures that the returned documents originate from official government organizations, reducing the likelihood of encountering unverified or unofficial sources.

---

### `cybersecurity`

Acts as the primary keyword.

Google searches for documents where the term **cybersecurity** appears in the title, URL, or content.

---

### `filetype:pdf`

Restricts the search results to PDF documents only.

This helps locate:

- Research papers
- Security frameworks
- Official guidelines
- Whitepapers
- Training material

while excluding normal web pages.

---

## Documents Discovered

Examples of documents found during the exercise include:

- Cybersecurity Basics (Federal Trade Commission)
- Common Cybersecurity Terminology (U.S. Election Assistance Commission)
- NIST Cybersecurity Framework (CSF) 2.0

---

## Why this Dork is Useful

Security professionals use this search to locate:

- Government security standards
- Compliance documents
- Security policies
- Incident response guides
- Technical documentation

---

## Cybersecurity Relevance

Google Dorking is widely used during Open Source Intelligence (OSINT) to gather publicly available information without directly interacting with the target system.

Searching for PDFs often uncovers valuable technical documents that may reveal:

- Security policies
- Network architecture
- Configuration guides
- Internal procedures
- Public security reports

## Conclusion

Using `site:.gov cybersecurity filetype:pdf` efficiently locates authoritative cybersecurity publications from trusted government agencies, making it an effective OSINT technique for research and security assessments.
