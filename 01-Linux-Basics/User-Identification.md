# User Identification

## Objective

Identify the currently logged-in user in the Linux system.

---

## Command Used

```bash
whoami
```

---

## Sample Output

```text
kali
```

---

## Explanation

The `whoami` command displays the username of the currently logged-in user.

It is commonly used to verify the identity under which commands are being executed, especially before performing administrative or security-sensitive tasks.

---

## Why this Command is Useful

- Verifies the current logged-in user.
- Confirms whether the session is running with normal user or root privileges.
- Useful while troubleshooting permission-related issues.
- Frequently used in shell scripts to validate user permissions before execution.

---

## Cybersecurity Relevance

During penetration testing and system administration, identifying the current user helps determine:

- Current privilege level
- Whether privilege escalation is required
- Access permissions available on the system

## Conclusion

The `whoami` command is one of the simplest yet most important Linux commands for identifying the active user and understanding the current security context of the terminal session.
