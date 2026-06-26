# Test Scenarios – Pawly Website

## 1. Home Page

| ID | Feature | Test Scenario |
|---|---|---|
| TS-001 | Home Page | Verify that the Home Page loads successfully |
| TS-002 | Home Page | Verify that the logo is displayed |
| TS-003 | Home Page | Verify that the main heading and description are displayed |
| TS-004 | Home Page | Verify that the “View Services” button is displayed and clickable |
| TS-005 | Home Page | Verify that service cards are displayed |
| TS-006 | Home Page | Verify that the footer is displayed correctly |

---

## 2. Navigation

| ID | Feature | Test Scenario |
|---|---|---|
| TS-007 | Navigation | Verify navigation to the Clinics page |
| TS-008 | Navigation | Verify navigation to the Grooming page |
| TS-009 | Navigation | Verify navigation to the Pet Shops page |
| TS-010 | Navigation | Verify navigation back to the Home Page using the logo |
| TS-011 | Navigation | Verify that the active page is highlighted in the navigation menu |

---

## 3. Registration

| ID | Feature | Test Scenario |
|---|---|---|
| TS-012 | Registration | Verify that the Registration modal opens |
| TS-013 | Registration | Verify successful registration with valid data |
| TS-014 | Registration | Verify registration with empty required fields |
| TS-015 | Registration | Verify registration with invalid email format |
| TS-016 | Registration | Verify registration with already registered email |
| TS-017 | Registration | Verify registration with password and confirm password mismatch |
| TS-018 | Registration | Verify password visibility toggle |
| TS-019 | Registration | Verify closing the Registration modal |

---

## 4. Login

| ID | Feature | Test Scenario |
|---|---|---|
| TS-020 | Login | Verify that the Login modal opens |
| TS-021 | Login | Verify successful login with valid credentials |
| TS-022 | Login | Verify login with empty required fields |
| TS-023 | Login | Verify login with invalid email format |
| TS-024 | Login | Verify login with incorrect password |
| TS-025 | Login | Verify password visibility toggle |
| TS-026 | Login | Verify closing the Login modal |

---

## 5. Forgot Password

| ID | Feature | Test Scenario |
|---|---|---|
| TS-027 | Forgot Password | Verify that the Forgot Password modal opens |
| TS-028 | Forgot Password | Verify password recovery request with valid email |
| TS-029 | Forgot Password | Verify password recovery request with empty email field |
| TS-030 | Forgot Password | Verify password recovery request with invalid email format |
| TS-031 | Forgot Password | Verify closing the Forgot Password modal |

---

## 6. User Profile

| ID | Feature | Test Scenario |
|---|---|---|
| TS-032 | User Profile | Verify that authorized user can open Profile page |
| TS-033 | User Profile | Verify that profile information is displayed |
| TS-034 | User Profile | Verify that unauthorized user cannot access protected profile actions |
| TS-035 | User Profile | Verify Edit Profile button behavior |
| TS-036 | User Profile | Verify Logout functionality |

---

## 7. Pet Management

| ID | Feature | Test Scenario |
|---|---|---|
| TS-037 | Pet Management | Verify that authorized user can open Add Pet page |
| TS-038 | Pet Management | Verify pet creation with valid data |
| TS-039 | Pet Management | Verify pet creation with empty required fields |
| TS-040 | Pet Management | Verify pet creation with invalid or unexpected input |
| TS-041 | Pet Management | Verify that created pet is displayed in the profile |
| TS-042 | Pet Management | Verify pet editing |
| TS-043 | Pet Management | Verify pet deletion |

---

## 8. Clinics

| ID | Feature | Test Scenario |
|---|---|---|
| TS-044 | Clinics | Verify that the Clinics page loads successfully |
| TS-045 | Clinics | Verify that clinic cards are displayed |
| TS-046 | Clinics | Verify that clinic name and address are displayed |
| TS-047 | Clinics | Verify search by clinic name |
| TS-048 | Clinics | Verify working hours filter |
| TS-049 | Clinics | Verify empty search result behavior |
| TS-050 | Clinics | Verify clinic markers on the map |

---

## 9. Grooming

| ID | Feature | Test Scenario |
|---|---|---|
| TS-051 | Grooming | Verify that the Grooming page loads successfully |
| TS-052 | Grooming | Verify that grooming cards are displayed |
| TS-053 | Grooming | Verify that grooming service name and address are displayed |
| TS-054 | Grooming | Verify search by grooming service name |
| TS-055 | Grooming | Verify working hours filter |
| TS-056 | Grooming | Verify empty search result behavior |
| TS-057 | Grooming | Verify grooming markers on the map |

---

## 10. Pet Shops

| ID | Feature | Test Scenario |
|---|---|---|
| TS-058 | Pet Shops | Verify that the Pet Shops page loads successfully |
| TS-059 | Pet Shops | Verify that shop cards are displayed |
| TS-060 | Pet Shops | Verify that shop name and address are displayed |
| TS-061 | Pet Shops | Verify search by shop name |
| TS-062 | Pet Shops | Verify working hours filter |
| TS-063 | Pet Shops | Verify empty search result behavior |
| TS-064 | Pet Shops | Verify shop markers on the map |

---

## 11. Map

| ID | Feature | Test Scenario |
|---|---|---|
| TS-065 | Map | Verify that the map is displayed on service pages |
| TS-066 | Map | Verify that location markers are displayed |
| TS-067 | Map | Verify switching between Map and Satellite view |
| TS-068 | Map | Verify map zoom controls |
| TS-069 | Map | Verify map fullscreen control |

---

## 12. Search and Filters

| ID | Feature | Test Scenario |
|---|---|---|
| TS-070 | Search and Filters | Verify search with valid service name |
| TS-071 | Search and Filters | Verify search with partial service name |
| TS-072 | Search and Filters | Verify search with non-existing service name |
| TS-073 | Search and Filters | Verify search field with special characters |
| TS-074 | Search and Filters | Verify filter reset behavior |

---

## 13. Basic Security

| ID | Feature | Test Scenario |
|---|---|---|
| TS-075 | Basic Security | Verify that unauthorized user cannot perform protected actions |
| TS-076 | Basic Security | Verify direct access to `/profile` without authentication |
| TS-077 | Basic Security | Verify direct access to `/petCreate` without authentication |
| TS-078 | Basic Security | Verify that JavaScript input is not executed in text fields |
| TS-079 | Basic Security | Verify that password is hidden by default |
| TS-080 | Basic Security | Verify that user session is removed after logout |

---

## 14. Basic Accessibility

| ID | Feature | Test Scenario |
|---|---|---|
| TS-081 | Accessibility | Verify that main buttons are visible and readable |
| TS-082 | Accessibility | Verify that form fields have visible labels or placeholders |
| TS-083 | Accessibility | Verify keyboard navigation through modal fields |
| TS-084 | Accessibility | Verify that focus is visible on interactive elements |
| TS-085 | Accessibility | Verify that important images do not block page usage |

