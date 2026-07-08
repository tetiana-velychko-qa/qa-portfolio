# Test Cases

## TC-001: Verify that the Home Page loads successfully

**Preconditions:**  
User is on the website URL.

**Steps:**
1. Open the website URL.

**Expected Result:**  
Home Page loads successfully without errors.

---

## TC-002: Verify that the "View Services" button is displayed and clickable

**Preconditions:**  
Home Page is opened.

**Steps:**
1. Check that the "View Services" button is displayed.
2. Click the "View Services" button.

**Expected Result:**  
The button is visible, clickable, and redirects the user to the services section or page.

---

## TC-003: Verify that service cards are displayed

**Preconditions:**  
Home Page is opened.

**Steps:**
1. Scroll to the services section.
2. Check service cards.

**Expected Result:**  
Service cards are displayed with correct information.

---

## TC-004: Verify navigation to the Clinics page

**Preconditions:**  
Home Page is opened.

**Steps:**
1. Click the "Clinics" navigation link.

**Expected Result:**  
User is redirected to the Clinics page.

---

## TC-005: Verify navigation back to the Home Page using the logo

**Preconditions:**  
User is on any page except Home Page.

**Steps:**
1. Click the website logo.

**Expected Result:**  
User is redirected to the Home Page.

---

## TC-006: Verify that the active page is highlighted in the navigation menu

**Preconditions:**  
User is on any website page.

**Steps:**
1. Open the Clinics page.
2. Check the navigation menu.

**Expected Result:**  
The active page is visually highlighted in the navigation menu.

---

## TC-007: Verify successful registration with valid data

**Preconditions:**  
Registration modal is opened.

**Steps:**
1. Enter a valid username.
2. Enter a valid email.
3. Enter a valid password.
4. Confirm the password.
5. Click the "Register" button.

**Expected Result:**  
User is successfully registered.

---

## TC-008: Verify registration with empty required fields

**Preconditions:**  
Registration modal is opened.

**Steps:**
1. Leave all required fields empty.
2. Click the "Register" button.

**Expected Result:**  
Registration is not completed. Validation messages are displayed.

---

## TC-009: Verify registration with invalid email format

**Preconditions:**  
Registration modal is opened.

**Steps:**
1. Enter a valid username.
2. Enter an invalid email format.
3. Enter a valid password.
4. Confirm the password.
5. Click the "Register" button.

**Expected Result:**  
Registration is not completed. Email validation message is displayed.

---

## TC-010: Verify registration with already registered email

**Preconditions:**  
Registration modal is opened. Email is already registered.

**Steps:**
1. Enter a valid username.
2. Enter an already registered email.
3. Enter a valid password.
4. Confirm the password.
5. Click the "Register" button.

**Expected Result:**  
Registration is not completed. Error message is displayed.

---
