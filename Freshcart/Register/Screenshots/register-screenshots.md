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
## 🐞 Bug 2 — Name Field Has No Maximum Character Limit

![Bug 2 Screenshot](bug2.png)

### Description
When the user enters a name with 100 characters and clicks Register, the system does not display any validation error.

Instead of showing an error message like "Name must not exceed character limit", the system registers the user successfully — meaning there is no maximum length validation on the name field.

### JIRA Ticket
🔗 [KAN-8 - Name Field Has No Maximum Character Limit](https://safynazibrahim4.atlassian.net/browse/KAN-8)

---

## 🐞 Bug 3 — Name Field Accepts Numbers Without Validation

![Bug 3 Screenshot](bug3.png)

### Description
When the user enters a name containing numbers (e.g., Safynaz123) and clicks Register, the system does not display any validation error.
Instead of showing an error message like "Name must contain letters only", the system registers the user successfully — meaning there is no letters-only validation on the name field.

### JIRA Ticket
🔗 [KAN-9 - Name Field Accepts Numbers Without Validation](https://safynazibrahim4.atlassian.net/browse/KAN-9)

---
