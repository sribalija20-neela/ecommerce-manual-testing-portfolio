# 🐛 Defect Tracking Log (Mock Jira Tickets)

This log contains the functional bugs identified during test execution.

### 🔴 BUG-01: Critical Security Vulnerability on Login Page
* **Severity:** High
* **Priority:** High
* **Environment:** Chrome Browser, Windows 11
* **Description:** The application allows a user to access the account dashboard even if they input an incorrect password.

#### Steps to Reproduce:
1. Navigate to the application Login page.
2. Enter a registered valid email address (`user@email.com`).
3. Enter an incorrect password value (`WrongPassword123`).
4. Click the "Login" button.

#### Results:
* **Expected Result:** Login blocks execution, remaining on the page with an error: "Incorrect password."
* **Actual Result:** User bypasses authentication and is granted full access to the dashboard profile page.
