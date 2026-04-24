# Register Screenshots - Bug Evidence

This file contains visual evidence of bugs found during testing of the Register functionality in the FreshCart application.

---

## 🐞 Bug 1 - Validation Error Message Not Displayed Correctly

![Bug 1 Screenshot](bug1.png)

### Description
When the user enters invalid data (e.g., name less than 3 characters) and clicks the Register button, the system does not display the correct validation message.

Instead of showing the specific error returned from the backend (e.g., "Name must be at least 3 characters"), the UI displays a generic message "fail".

This prevents the user from understanding the exact issue and how to fix it.

### Jira Ticket
🔗 [KAN-7 - Validation Error Message Issue](https://safynazibrahim4.atlassian.net/browse/KAN-7)

---
