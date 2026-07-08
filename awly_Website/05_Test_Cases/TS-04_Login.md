# Test Suite: Login

## OVERVIEW
https://pawlyapp.me/

## COMMON ADDITIONAL INFO
| | |
|---|---|
| **Test environment** | Production |
| **Browser** | Chrome |
| **OS** | MacOS (Sequoia) |

## Test Cases

| Test Case ID | Summary (Title) | Additional info | Steps to perform | Expected Result | Priority | Status |
|---|---|---|---|---|---|---|
| TC021 | Verify successful login with valid credentials | Email: registereduser@test.com<br>Password: Test1234! | 1. Open the Login page.<br>2. Enter valid registered email.<br>3. Enter valid password.<br>4. Click "Login" button. | User is successfully authenticated; user is redirected to the dashboard/home page; session is established. | High | Passed |
| TC022 | Verify login with empty required fields | — | 1. Open the Login page.<br>2. Leave email and password fields empty.<br>3. Click "Login" button. | Validation error messages are displayed for each empty required field; login is not submitted. | Medium | Passed |
| TC024 | Verify login with incorrect password | Email: registereduser@test.com<br>Password: WrongPass1! | 1. Open the Login page.<br>2. Enter valid registered email.<br>3. Enter an incorrect password.<br>4. Click "Login" button. | Error message is displayed (e.g., "Invalid email or password"); user is not authenticated. | High | Passed |
