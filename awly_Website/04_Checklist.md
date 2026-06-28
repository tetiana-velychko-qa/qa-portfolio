# Checklist – Pawly Website

## Home Page

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 1 | Verify Home page loads successfully | High |  🟢 Passed | |
| 2 | Verify logo is displayed | Low |  🟢 Passed | |
| 3 | Verify navigation menu is displayed | High |  🟢 Passed | |
| 4 | Verify hero section is displayed | Medium | 🟢 Passed | |
| 5 | Verify "View Services" button works | High |  🟢 Passed | |
| 6 | Verify Featured Services section is displayed | Medium |  🟢 Passed | |
| 7 | Verify footer is displayed correctly | Low |  🟢 Passed | |

---

## Navigation

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 8 | Verify navigation to Clinics page | High |  🟢 Passed | |
| 9 | Verify navigation to Grooming page | High |  🟢 Passed | |
| 10 | Verify navigation to Pet Shops page | High |  🟢 Passed| |
| 11 | Verify navigation to Home page using logo | Medium |  🟢 Passed | |

---

## Registration

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 13 | Verify Registration modal opens | High |🟢 Passed | |
| 14 | Verify successful registration with valid data | High | 🟢 Passed | |
| 15 | Verify registration with invalid email | Medium | 🟢 Passed | |
| 16 | Verify registration with existing email | Medium | 🟢 Passed | |
| 17 | Verify registration with mismatched passwords | Medium | 🟢 Passed | |
| 18 | Verify registration with empty required fields | Medium | 🟢 Passed | |
| 19 | Verify password visibility toggle | Low | 🟢 Passed| |
| 20 | Verify Registration modal closes correctly | Low | 🟢 Passed | |

---

## Login

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 21 | Verify Login modal opens | High | 🟢 Passed | |
| 22 | Verify login with valid credentials | High | 🟢 Passed | |
| 23 | Verify login with invalid credentials | High | 🟢 Passed| |
| 24 | Verify login with empty required fields | Medium |🟢 Passed | |
| 25 | Verify password visibility toggle | Low | 🟢 Passed | |
| 26 | Verify Login modal closes correctly | Low | 🟢 Passed | |

---

## Forgot Password

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 27 | Verify Forgot Password modal opens | Medium |  🟢 Passed| |
| 28 | Verify password recovery with valid email | High |  🟢 Passed | |
| 29 | Verify password recovery with invalid email | Medium |  🟢 Passed | |
| 30 | Verify password recovery with empty email | Medium |  🟢 Passed | |
| 31 | Verify Forgot Password modal closes correctly | Low |  🟢 Passed | |

---

## User Profile

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 32 | Verify Profile page opens | High |  🟢 Passed | |
| 33 | Verify profile information is displayed | Medium |  🟢 Passed | |
| 34 | Verify Edit Profile functionality | High |  🟢 Passed | |
| 35 | Verify Logout functionality | High | 🟢 Passed | |
| 36 | Verify unauthorized user cannot access /profile via direct URL | High | 🔴 Failed |[BR-004](./06_Bug_Reports/BR-004_Unauthorized_Profile_Access.md) |
| 37 | Verify unauthorized user cannot access /profile via direct URL | High | 🔴 Failed | [BR-004](./06_Bug_Reports/BR-004_Unauthorized_Profile_Access.md)|
---

## Pet Management

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 37 | Verify Add Pet page opens | High |  🟢 Passed | |
| 38 | Verify pet creation with valid data | High |  🟢 Passed | |
| 39 | Verify required field validation | Medium |  🟢 Passed | |
| 40 | Verify invalid input validation | Medium |  🟢 Passed | |
| 41 | Verify created pet is displayed | Medium |  🟢 Passed | |
| 42 | Verify pet editing | High |  🟢 Passed | |
| 43 | Verify pet deletion | High |  🟢 Passed | |

---

## Clinics

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 44 | Verify Clinics page opens | High | 🟢 Passed | |
| 45 | Verify clinic cards are displayed | Medium | 🟢 Passed | |
| 46 | Verify clinic search | High | 🟢 Passed | |
| 47 | Verify working hours filter | Medium | 🟢 Passed | |
| 48 | Verify empty search result | Low | 🟢 Passed | |
| 49 | Verify clinic markers on the map | Medium | 🟢 Passed  | |

---

## Grooming

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 50 | Verify Grooming page opens | High | 🟢 Passed  | |
| 51 | Verify grooming cards are displayed | Medium | 🟢 Passed  | |
| 52 | Verify grooming search | High | 🟢 Passed  | |
| 53 | Verify working hours filter | Medium | 🟢 Passed  | |
| 54 | Verify empty search result | Low |🟢 Passed  | |
| 55 | Verify grooming markers on the map | Medium | 🟢 Passed | |

---

## Pet Shops

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 56 | Verify Pet Shops page opens | High | 🟢 Passed | |
| 57 | Verify shop cards are displayed | Medium | 🟢 Passed | |
| 58 | Verify shop search | High | 🟢 Passed| |
| 59 | Verify working hours filter | Medium | 🟢 Passed | |
| 60 | Verify empty search result | Low | 🟢 Passed | |
| 61 | Verify shop markers on the map | Medium | 🟢 Passed | |

---

## Map

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 62 | Verify map is displayed | Medium | 🟢 Passed | |
| 63 | Verify location markers | Medium | 🟢 Passed | |
| 64 | Verify zoom controls | Low | 🟢 Passed | |
| 66 | Verify satellite view | Low | 🟢 Passed | |

---

## Basic Security

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 67 | Verify unauthorized user cannot access protected actions | High | 🔴 Failed | [BR-004](./06_Bug_Reports/BR-004_Unauthorized_Profile_Access.md) |
| 68 | Verify direct access to `/profile` | High | 🔴 Failed| [BR-004](./06_Bug_Reports/BR-004_Unauthorized_Profile_Access.md) |
| 69 | Verify direct access to `/petCreate` | High |🔴 Failed | [BR-004](./06_Bug_Reports/BR-004_Unauthorized_Profile_Access.md) |
| 70 | Verify JavaScript input is not executed | Medium | 🟢 Passed | |
| 71 | Verify password is hidden by default | Low | 🟢 Passed | |
| 72 | Verify session is cleared after logout | High | 🟢 Passed | |

---

## Basic Accessibility

| # | Checklist Item | Priority | Result | Comment |
|---|----------------|----------|--------|---------|
| 73 | Verify buttons are readable | Low | 🟢 Passed | |
| 74 | Verify inputs have labels/placeholders | Medium | 🟢 Passed | |
| 75 | Verify keyboard navigation | Medium | 🟢 Passed | |
| 76 | Verify focus visibility | Low | 🟢 Passed | |
| 77 | Verify images do not affect usability | Low | 🟢 Passed | |
