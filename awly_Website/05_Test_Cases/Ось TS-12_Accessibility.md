# Test Suite: Accessibility

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
| TC083 | Verify keyboard navigation through modal fields | — | 1. Open a modal window (e.g., Login, Add Pet, Registration).<br>2. Use the "Tab" key to move focus through all fields.<br>3. Use "Shift + Tab" to move focus backward.<br>4. Press "Esc" to close the modal. | Focus moves logically through all interactive elements in the modal in the correct order; modal closes with "Esc"; no focus trap outside the modal occurs. | Low | Passed |
