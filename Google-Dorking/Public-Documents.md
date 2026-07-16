# Google Dorking – Public Documents

## Objective

Discover publicly accessible documents hosted on a target website using Google Dorking techniques.

---

## Google Dorks Used

```text
site:google.com filetype:pdf
```

```text
site:google.com filetype:xls
```

---

## Explanation of Search Operators

### `site:google.com`

Limits the search to documents hosted only on the specified domain.

---

### `filetype:pdf`

Searches exclusively for PDF documents.

Common examples include:

- Reports
- Manuals
- Whitepapers
- Policies
- Technical Documentation

---

### `filetype:xls`

Searches specifically for Microsoft Excel spreadsheets.

These may contain:

- Data reports
- Statistics
- Inventories
- Public datasets

---

## Why Public Documents Matter

Organizations often publish documents containing useful technical information.

These may include:

- User manuals
- Product documentation
- Research reports
- Public datasets
- Technical specifications

---

## Cybersecurity Relevance

During Open Source Intelligence (OSINT), publicly available documents may unintentionally expose valuable information such as:

- Employee names
- Internal file paths
- Software versions
- Email addresses
- Metadata
- Organizational structure

Security analysts review publicly available documents to identify information exposure risks while remaining within legal and ethical boundaries.

---

## Best Practices

- Access only information that is publicly available.
- Do not attempt to bypass authentication or access controls.
- Follow responsible disclosure practices if sensitive information is discovered.

## Conclusion

Google Dorking enables security professionals to efficiently locate publicly available documents that can support OSINT investigations and help identify potential information disclosure risks.
