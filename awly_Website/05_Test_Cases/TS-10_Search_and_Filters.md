# Test Suite: Search and Filters

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
| TC072 | Verify search with non-existing service name | Search query: "Nonexistent Service XYZ" | 1. Navigate to the Services search page.<br>2. Enter a service name that does not exist.<br>3. Submit/execute the search. | No results message is displayed (e.g., "No services found"); no service cards are shown; no error/crash occurs. | Medium | Passed |
