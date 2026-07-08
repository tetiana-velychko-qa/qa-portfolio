# Test Suite: Home Page

## OVERVIEW
https://pawly-app.com (заміни на реальний URL)

## COMMON ADDITIONAL INFO
| | |
|---|---|
| **Test environment** | Production |
| **Browser** | Chrome |
| **OS** | MacOS (Sequoia) |

## Test Cases

| Test Case ID | Summary (Title) | Additional info | Steps to perform | Expected Result | Priority | Status |
|---|---|---|---|---|---|---|
| TC001 | Verify that the Home Page loads successfully | — | 1. Open browser.<br>2. Navigate to Pawly home page URL.<br>3. Wait for page to fully load. | Home Page loads without errors; all key elements (header, navigation, main content) are visible. | Critical | Passed |
| TC004 | Verify that the "View Services" button is displayed and clickable | — | 1. Locate "View Services" button on Home Page.<br>2. Verify button is visible.<br>3. Click "View Services" button. | Button is visible and enabled; clicking it navigates the user to the Services page. | High | Passed |
| TC005 | Verify that service cards are displayed | — | 1. Scroll to the service cards section.<br>2. Verify cards are rendered.<br>3. Verify each card contains expected info (icon/image, title, short description). | Service cards are displayed correctly with all expected content; no broken images or missing text. | Medium | Passed |
