# 📧 Gmail Manual Testing Project



This project documents the manual testing of Gmail's core functionalities by creating structured test cases in Microsoft Excel. The purpose of this project is to practice writing professional test cases using an industry-standard format and improve software testing documentation skills.



## Project Overview

Manual testing is a software testing technique where test cases are executed manually without using automation tools. A well-written test case helps verify whether an application's functionality works as expected and ensures that defects can be identified efficiently.

In this project, test cases were created for some of Gmail's most commonly used features. Each test case includes all the necessary details required for proper test execution and documentation.

## Test Case Format

Each test case follows the standard QA documentation format:

- Test Case ID
- Test Case Scenario
- Title
- Preconditions
- Test Steps
- Postconditions
- Test Data
- Expected Result
- Actual Result
- Remarks


## Functionalities Tested

- Login
- Sign Up
- Homepage
- Search Email
- Star Email
- Unstar Email
- Delete Email
- Trash
- Restore Email
- Create Label
- Apply Label
- Compose Email
- Sent Mail
- Logout



## Test Case Summary

| Module | Test Cases |
|---------|-----------:|
| Login | 2 |
| Sign Up | 1 |
| Homepage | 1 |
| Search | 1 |
| Star / Unstar | 2 |
| Delete / Trash / Restore | 3 |
| Labels | 2 |
| Compose & Sent Mail | 2 |
| Logout | 1 |

**Total Test Cases:** **15**


## Sample Test Case

| Field | Description |
|-------|-------------|
| **Test Case ID** | TC_GMAIL_001 |
| **Scenario** | Login |
| **Title** | Verify login with valid credentials |
| **Preconditions** | User has a registered Gmail account |
| **Steps** | Open Gmail → Enter valid email → Click Next → Enter password → Click Sign In |
| **Postconditions** | User is successfully logged in |
| **Test Data** | Email: testuser@gmail.com Password: Test@123 |
| **Expected Result** | Inbox page should be displayed |
| **Actual Result** | Pass |
| **Remarks** | Working as expected |

### 🎯 Day 8 Completed!