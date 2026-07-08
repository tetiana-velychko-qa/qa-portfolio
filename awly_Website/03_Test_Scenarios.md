## 1. Home Page

| ID | Feature | Test Scenario |
|----|---------|---------------|
| TS-001 | Home Page | Verify that the Home Page loads successfully |
| TS-004 | Home Page | Verify that the "View Services" button is displayed and clickable |
| TS-005 | Home Page | Verify that service cards are displayed |

## 2. Navigation

| ID | Feature | Test Scenario |
|----|---------|---------------|
| TS-007 | Navigation | Verify navigation to the Clinics page |
| TS-010 | Navigation | Verify navigation back to the Home Page using the logo |
| TS-011 | Navigation | Verify that the active page is highlighted in the navigation menu |

## 3. Registration

| ID | Feature | Test Scenario |
|----|---------|---------------|
| TS-013 | Registration | Verify successful registration with valid data |
| TS-014 | Registration | Verify registration with empty required fields |
| TS-015 | Registration | Verify registration with invalid email format |
| TS-016 | Registration | Verify registration with already registered email |
| TS-017 | Registration | Verify registration with password and confirm password mismatch |

## 4. Login

| ID | Feature | Test Scenario |
|----|---------|---------------|
| TS-021 | Login | Verify successful login with valid credentials |
| TS-022 | Login | Verify login with empty required fields |
| TS-024 | Login | Verify login with incorrect password |

## 5. Forgot Password

| ID | Feature | Test Scenario |
|----|---------|---------------|
| TS-028 | Forgot Password | Verify password recovery request with valid email |
| TS-030 | Forgot Password | Verify password recovery request with invalid email format |

## 6. User Profile

| ID | Feature | Test Scenario |
|----|---------|---------------|
| TS-032 | User Profile | Verify that authorized user can open Profile page |
| TS-034 | User Profile | Verify that unauthorized user cannot access protected profile actions |
| TS-036 | User Profile | Verify Logout functionality |

## 7. Pet Management

| ID | Feature | Test Scenario |
|----|---------|---------------|
| TS-038 | Pet Management | Verify pet creation with valid data |
| TS-039 | Pet Management | Verify pet creation with empty required fields |
| TS-042 | Pet Management | Verify pet editing |
| TS-043 | Pet Management | Verify pet deletion |

## 8. Clinics

| ID | Feature | Test Scenario |
|----|---------|---------------|
| TS-047 | Clinics | Verify search by clinic name |
| TS-049 | Clinics | Verify empty search result behavior |

## 9. Map

| ID | Feature | Test Scenario |
|----|---------|---------------|
| TS-067 | Map | Verify switching between Map and Satellite view |

## 10. Search and Filters

| ID | Feature | Test Scenario |
|----|---------|---------------|
| TS-072 | Search and Filters | Verify search with non-existing service name |

## 11. Basic Security

| ID | Feature | Test Scenario |
|----|---------|---------------|
| TS-076 | Basic Security | Verify direct access to /profile without authentication |
| TS-078 | Basic Security | Verify that JavaScript input is not executed in text fields |

## 12. Basic Accessibility

| ID | Feature | Test Scenario |
|----|---------|---------------|
| TS-083 | Accessibility | Verify keyboard navigation through modal fields |
