# Test Suite: Pet Management

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
| TC038 | Verify pet creation with valid data | Pet name: Rex<br>Type: Dog<br>Breed: Labrador | 1. Log in with valid credentials.<br>2. Navigate to "Add Pet" section.<br>3. Enter all required fields with valid data.<br>4. Click "Save"/"Add Pet" button. | Pet is successfully created and displayed in the user's pet list with the entered information. | High | Passed |
| TC039 | Verify pet creation with empty required fields | — | 1. Log in with valid credentials.<br>2. Navigate to "Add Pet" section.<br>3. Leave required fields empty.<br>4. Click "Save"/"Add Pet" button. | Validation error messages are displayed for each empty required field; pet is not created. | Medium | Passed |
| TC042 | Verify pet editing | Pet name: Rex → Max | 1. Log in with valid credentials.<br>2. Navigate to an existing pet's profile.<br>3. Click "Edit".<br>4. Change one or more fields (e.g., pet name).<br>5. Click "Save". | Pet information is updated successfully; changes are reflected in the pet's profile/list. | Medium | Passed |
| TC043 | Verify pet deletion | Pet name: Max | 1. Log in with valid credentials.<br>2. Navigate to an existing pet's profile.<br>3. Click "Delete".<br>4. Confirm deletion if prompted. | Pet is removed from the user's pet list; pet profile is no longer accessible. | Medium | Passed |
