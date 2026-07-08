# Test Suite: Registration

## OVERVIEW
[https://pawly-app.com (заміни на реальний URL)](https://pawlyapp.me/)

## COMMON ADDITIONAL INFO
| | |
|---|---|
| **Test environment** | Production |
| **Browser** | Chrome |
| **OS** | MacOS (Sequoia) |

## Test Cases

| Test Case ID | Summary (Title) | Additional info | Steps to perform | Expected Result | Priority | Status |
|---|---|---|---|---|---|---|
| TC013 | Verify successful registration with valid data | Email: newuser@test.com<br>Password: Test1234! | 1. Open the Registration page.<br>2. Enter valid first name, last name.<br>3. Enter valid, unused email.<br>4. Enter valid password and matching confirm password.<br>5. Click "Sign Up" button. | User is successfully registered; success message is displayed; user is redirected to Login/Home page. | High | Passed |
| TC014 | Verify registration with empty required fields | — | 1. Open the Registration page.<br>2. Leave all required fields empty.<br>3. Click "Sign Up" button. | Validation error messages are displayed for each empty required field; registration is not submitted. | Medium | Passed |
| TC015 | Verify registration with invalid email format | Email: test@test | 1. Open the Registration page.<br>2. Enter valid data in all fields.<br>3. Enter an invalid email format.<br>4. Click "Sign Up" button. | Validation error is displayed indicating invalid email format; registration is not submitted. | Medium | Passed |
| TC016 | Verify registration with already registered email | Email: existing@test.com | 1. Open the Registration page.<br>2. Enter valid data in all fields.<br>3. Enter an email that is already registered.<br>4. Click "Sign Up" button. | Error message is displayed (e.g., "Email already in use"); registration is blocked. | High | Passed |
| TC017 | Verify registration with password and confirm password mismatch | — | 1. Open the Registration page.<br>2. Enter valid data in all fields.<br>3. Enter a password.<br>4. Enter a different value in confirm password field.<br>5. Click "Sign Up" button. | Validation error is displayed indicating passwords do not match; registration is not submitted. | Medium | Passed |
