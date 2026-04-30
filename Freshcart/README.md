# FreshCart Testing Project

This project is a manual testing practice on a real e-commerce web application (FreshCart), originally developed as a frontend project. The goal is to apply professional software testing concepts including test case design, test execution, bug reporting, and documentation.

---

## 📌 Project Objective

Apply software testing concepts by designing and executing structured test cases for FreshCart functionalities, reporting bugs using Jira, and documenting all findings professionally on GitHub.

---

## 🔍 Scope of Testing

### ✅ Login Functionality (Completed)
- Valid & invalid login scenarios
- Input validation
- Negative testing

### ✅ Register Functionality (Completed)
- Full validation for all fields (Name, Email, Password, Repassword, Phone)
- Boundary Value Analysis & Equivalence Partitioning

### ✅ User Flow Testing (NEW 🔥)
End-to-end testing covering real user journey:

- Login → Browse → Search → View Product → Add to Cart → Manage Cart

Covered:
- Product listing & UI validation
- Search functionality (valid, invalid, edge cases)
- Product details & images slider
- Add to cart & toast behavior
- Cart operations (زيادة / تقليل / حذف)
- Cart persistence (refresh + re-login)

---

## 📊 Testing Summary

| Module | Total Test Cases | Bugs Found | Improvements |
|---|---|---|---|
| Login | 10 | 3 | 1 |
| Register | 44 | 8 | 1 |
| User Flow | 30 | 5 | 0 |
| **Total** | **84** | **16** | **2** |

---

## 🐛 Key Bugs Found (User Flow)

- 🔴 Search returns irrelevant results (wrong matching logic)
- 🔴 No feedback message when search returns no results
- 🔴 Cart shows blank page after removing last item
- 🔴 Minus button still clickable at quantity = 1
- 🔴 No feedback for invalid numeric search

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Jira | Bug tracking |
| GitHub | Documentation |
| Google Sheets | Test cases |
| DevTools | Debugging |
| Manual Testing | Execution |

---

## 💡 Summary

This project reflects my transition from Frontend Development to Software Testing.

I am not only testing individual features, but also validating full user journeys, identifying real-world issues, and improving overall user experience.
