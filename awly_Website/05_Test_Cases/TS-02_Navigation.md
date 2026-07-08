# Test Suite: Navigation

## OVERVIEW
[https://pawly-app.com](https://pawlyapp.me/)

## COMMON ADDITIONAL INFO
| | |
|---|---|
| **Test environment** | Production |
| **Browser** | Chrome |
| **OS** | MacOS (Sequoia) |

## Test Cases

| Test Case ID | Summary (Title) | Additional info | Steps to perform | Expected Result | Priority | Status |
|---|---|---|---|---|---|---|
| TC007 | Verify navigation to the Clinics page | — | 1. Open the Home Page.<br>2. Locate "Clinics" link/button in the navigation menu.<br>3. Click on "Clinics". | User is redirected to the Clinics page; page content (clinics list/search) loads correctly. | High | Passed |
| TC010 | Verify navigation back to the Home Page using the logo | — | 1. Open any internal page (e.g., Clinics, Login).<br>2. Locate the Pawly logo in the header.<br>3. Click on the logo. | User is redirected to the Home Page. | Medium | Passed |
| TC011 | Verify that the active page is highlighted in the navigation menu | — | 1. Open the Home Page.<br>2. Click on a navigation menu item (e.g., "Clinics").<br>3. Observe the navigation menu after page loads.<br>4. Repeat for another menu item. | The corresponding menu item is visually highlighted/marked as active, matching the currently open page. | Low | Passed |
