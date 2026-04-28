# User Flow Screenshots - Bug Evidence

This file contains visual evidence of bugs found during testing of the User Flow functionality in the FreshCart application.

---

## 🐞 Bug 1 — Search Returns Irrelevant Products Not Matching Keyword

![Bug 1 Screenshot](userflow-bug1.png)

### Description
When the user searches for "sock", the system returns irrelevant results.

Expected products to appear:
- Woman Socks ✅
- Woman Karma Socks ✅

Product that should NOT appear:
- NSW Everyday Essentials ❌ — name does not contain "sock"

Search is likely matching by category instead of product name only.
This gives the user irrelevant results and affects search accuracy.

### JIRA Ticket
🔗 [https://safynazibrahim4.atlassian.net/browse/KAN-16]

---
