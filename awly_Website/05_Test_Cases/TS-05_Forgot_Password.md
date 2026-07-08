# Test Suite: Forgot Password

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
| TC028 | Verify password recovery request with valid email | Email: registereduser@test.com | 1. Open the Login page.<br>2. Click "Forgot Password" link.<br>3. Enter a valid, registered email.<br>4. Click "Submit"/"Send" button. | Confirmation message is displayed (e.g., "Reset link sent to your email"); a password reset email is delivered to the specified address. | High | Passed |
| TC030 | Verify password recovery request with invalid email format | Email: test@test | 1. Open the Login page.<br>2. Click "Forgot Password" link.<br>3. Enter an invalid email format.<br>4. Click "Submit"/"Send" button. | Validation error is displayed indicating invalid email format; request is not submitted. | Medium | Passed |
