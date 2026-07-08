# Test Suite: Home Page

**Related Scenarios:** TS-001, TS-004, TS-005
**Feature:** Home Page
**Total Test Cases:** 3

| TC ID | Title | Priority | Preconditions | Steps | Expected Result | Status |
|---|---|---|---|---|---|---|
| TC-001 | Verify Home Page loads successfully | High | User has internet access; Pawly URL is available | 1. Open browser<br>2. Navigate to Pawly home page URL<br>3. Wait for page to fully load | Home Page loads without errors; all key elements (header, navigation, main content) are visible within acceptable load time | Pass |
| TC-004 | Verify "View Services" button is displayed and clickable | High | User is on the Home Page | 1. Locate "View Services" button on Home Page<br>2. Verify button is visible<br>3. Click "View Services" button | Button is visible and enabled; clicking it navigates user to the Services page | Pass |
| TC-005 | Verify service cards are displayed | Medium | User is on the Home Page | 1. Scroll to service cards section<br>2. Verify cards are rendered<br>3. Verify each card contains expected info (icon/image, title, short description) | Service cards are displayed correctly with all expected content, no broken images or missing text | Pass |
