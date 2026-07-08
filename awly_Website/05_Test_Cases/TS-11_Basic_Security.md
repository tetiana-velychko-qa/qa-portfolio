# Test Suite: Basic Security

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
| TC076 | Verify direct access to /profile without authentication | — | 1. Log out (or open in incognito, not logged in).<br>2. Manually enter the direct URL to `/profile` in the browser address bar.<br>3. Press Enter. | User is redirected to the Login page or an access-denied message is shown; profile content/data is not exposed. | High | Failed awly_Website/06_Bug_Reports/BR-004_Unauthorized_Profile_Access.md |
| TC078 | Verify that JavaScript input is not executed in text fields | Input: `<script>alert('XSS')</script>` | 1. Navigate to a page with a text input field (e.g., search, pet name, comment).<br>2. Enter a script-based payload into the field.<br>3. Submit the form. | The script is not executed (no alert/popup appears); input is either sanitized, escaped, or rejected by validation. | High | Passed |
