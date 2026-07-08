# Test Suite: Navigation

**Related Scenarios:** TS-007, TS-010, TS-011
**Feature:** Navigation
**Total Test Cases:** 3

| TC ID | Title | Priority | Preconditions | Steps | Expected Result | Status |
|---|---|---|---|---|---|---|
| TC-007 | Verify navigation to the Clinics page | High | User is on the Home Page | 1. Locate "Clinics" link/button in the navigation menu<br>2. Click on "Clinics"<br>3. Observe the page transition | User is redirected to the Clinics page; page content (clinics list/search) loads correctly | Pass |
| TC-010 | Verify navigation back to the Home Page using the logo | Medium | User is on any internal page (e.g., Clinics, Login) | 1. Locate the Pawly logo in the header<br>2. Click on the logo<br>3. Observe the page transition | User is redirected to the Home Page | Pass |
| TC-011 | Verify that the active page is highlighted in the navigation menu | Low | User is on the Home Page | 1. Click on a navigation menu item (e.g., "Clinics")<br>2. Observe the navigation menu after page loads<br>3. Repeat for another menu item | The corresponding menu item is visually highlighted/marked as active, matching the currently open page | Pass |

## Notes
- All test cases executed on Chrome 126, desktop resolution 1920x1080.
