# Test Suite: Clinics

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
| TC047 | Verify search by clinic name | Search query: "VetCare" | 1. Navigate to the Clinics page.<br>2. Enter a valid clinic name into the search field.<br>3. Submit/execute the search. | Search results display the clinic(s) matching the entered name; relevant results are shown correctly. | Medium | Passed |
| TC049 | Verify empty search result behavior | Search query: "Nonexistent Clinic XYZ" | 1. Navigate to the Clinics page.<br>2. Enter a clinic name that does not exist.<br>3. Submit/execute the search. | No results message is displayed (e.g., "No clinics found"); no clinic cards are shown; no error/crash occurs. | Medium | Passed |
