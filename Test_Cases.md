# 📋 Test Case Suite - E-Commerce Web Application

This document contains the functional positive, negative, and boundary-value test cases designed for an E-Commerce platform.

## 🔐 Module 1: User Login & Authentication

| Test Case ID | Test Scenario | Test Steps | Expected Result | Status |
| :--- | :--- | :--- | :--- | :--- |
| **TC-01 (Positive)** | Valid login execution | 1. Navigate to Login page.<br>2. Enter valid email.<br>3. Enter valid password.<br>4. Click Login button. | User logs in successfully and sees their account profile dashboard. | PASS |
| **TC-02 (Negative)** | Login with incorrect password | 1. Navigate to Login page.<br>2. Enter valid email.<br>3. Enter an incorrect password.<br>4. Click Login button. | Login fails. System displays error message: "Incorrect password." | PASS |

## 🔍 Module 2: Search & Discovery (Streaming Platform Scenario)

| Test Case ID | Test Scenario | Test Steps | Expected Result | Status |
| :--- | :--- | :--- | :--- | :--- |
| **TC-03 (Positive)** | Searching for an exact movie title | 1. Click on the video search bar.<br>2. Type "Stranger Things".<br>3. Press the Enter key. | The grid updates instantly to show the "Stranger Things" show banner and episodes. | PASS |
| **TC-04 (Negative)** | Handling completely blank spaces | 1. Click on the search bar.<br>2. Press the Spacebar 5 times.<br>3. Click the search magnifying glass. | System ignores the empty spaces and does not refresh or display an error page. | PASS |


## 🛒 Module 3: Shopping Cart

| Test Case ID | Test Scenario | Test Steps | Expected Result | Status |
| :--- | :--- | :--- | :--- | :--- |
| **TC-05 (Positive)** | Removing item from cart | 1. Open Shopping Cart page.<br>2. Click "Delete" button next to item. | Item disappears from list, cart count drops by 1, and price updates. | PASS |
| **TC-06 (Boundary)** | Testing max item quantity limits | 1. Open product page.<br>2. Change quantity dropdown to 10.<br>3. Click "Add to Cart". | Cart accepts the batch, updating quantity count to 10 successfully. | PASS |
