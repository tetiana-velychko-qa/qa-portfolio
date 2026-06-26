# Test Plan – Pawly Website

## 1. Project Overview

**Project Name:** Pawly Website

**Project Description:**  
Pawly is a web application for pet owners that helps users find pet-related services, including veterinary clinics, grooming services, and pet shops. The website also allows users to manage their profile and add information about their pets.

---

## 2. Testing Objective

The objective of testing is to verify that the Pawly website works correctly, provides a clear user experience, and handles the main user flows without critical issues.

---

## 3. Scope

### In Scope

The following areas are included in testing:

- Home Page
- Navigation
- User Registration
- User Login
- Password Recovery
- User Profile
- Pet Management
- Veterinary Clinics
- Grooming Services
- Pet Shops
- Search
- Filters
- Map
- Responsive UI
- API Testing
- Basic Security Testing
- Basic Accessibility Testing

### Out of Scope

The following areas are not included in testing:

- Performance Testing
- Load Testing
- Mobile Application Testing
- Payment and Transaction Testing
- Localization and Internationalization Testing for multiple language support

---

## 4. Testing Types

The following testing types will be performed:

- Functional Testing
- UI Testing
- Smoke Testing
- Regression Testing
- Exploratory Testing
- API Testing
- Basic Security Testing
- Basic Accessibility Testing

---

## 5. Test Environment

| Item | Value |
|---|---|
| Operating System | macOS |
| Browser | Google Chrome |
| Frontend | React + Vite |
| Backend | Docker |
| Testing Type | Manual Testing |
| API Testing Tool | Postman |
| Documentation Tool | GitHub |

---

## 6. Test Deliverables

The following QA documentation will be created:

- Test Plan
- Feature Decomposition
- Test Scenarios
- Checklist
- Test Cases
- Bug Reports
- Test Summary Report

---

## 7. Entry Criteria

Testing can begin when:

- The project repository is available on GitHub.
- The project is cloned locally (if testing a local environment).
- Required dependencies are installed.
- Frontend is successfully launched locally or the deployed website is available.
- Backend is successfully launched using Docker (if testing a local environment).
- The website is accessible in the browser.
- Main functionality is implemented and ready for testing.
- Basic requirements or expected behavior are understood.

---

## 8. Exit Criteria

Testing is considered complete when:

- All planned test cases have been executed.
- Main user flows have been tested.
- Critical and High severity defects have been reported.
- Blocking defects have been resolved or documented.
- Test documentation has been completed.
- Test Summary Report has been prepared.

---

## 9. Risks

Potential risks include:

- Requirements may be incomplete or unclear.
- Functionality may change during testing.
- Backend may be unstable.
- Test data may be limited.
- Browser translation may affect language-related checks.
- Performance and load testing are not performed because they may affect the shared test environment.

---

## 10. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| QA Engineer | Create test documentation, execute tests, report defects |
| Developer | Fix reported defects |
| Team | Review requirements, clarify expected behavior, and review testing results |

---

## 11. Tools

The following tools are used during testing:

- GitHub
- Jira
- Google Chrome
- Chrome DevTools
- Postman
- VS Code
- Docker

---

## 12. Bug Severity Levels

| Severity | Description |
|---|---|
| Critical | The system is unavailable or core functionality cannot be used. |
| High | Major functionality does not work correctly and has no acceptable workaround. |
| Medium | Functionality works incorrectly, but there is a workaround or the issue affects a limited flow. |
| Low | Minor issue related to UI, text, validation, accessibility, localization, or cosmetic behavior. |

---

## 13. Bug Priority Levels

| Priority | Description |
|---|---|
| High | Should be fixed as soon as possible. |
| Medium | Should be fixed in the current or upcoming iteration. |
| Low | Can be fixed later and does not block main functionality. |

---

