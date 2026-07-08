# Test Suite: User Profile

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
| TC032 | Verify that authorized user can open Profile page | Email: registereduser@test.com<br>Password: Test1234! | 1. Log in with valid credentials.<br>2. Locate the Profile menu/icon.<br>3. Click on Profile. | User is redirected to the Profile page; user's account information is displayed correctly. | High | Passed |
| TC034 | Verify that unauthorized user cannot access protected profile actions | — | 1. Log out (or open in incognito, not logged in).<br>2. Attempt to directly navigate to the Profile page URL.<br>3. Observe the result. | User is redirected to the Login page or an access-denied message is shown; profile actions are not accessible. | High | Passed |
| TC036 | Verify Logout functionality | Email: registereduser@test.com<br>Password: Test1234! | 1. Log in with valid credentials.<br>2. Open Profile or header menu.<br>3. Click "Logout". | User session is terminated; user is redirected to the Login/Home page; protected pages are no longer accessible. | High | Passed |
