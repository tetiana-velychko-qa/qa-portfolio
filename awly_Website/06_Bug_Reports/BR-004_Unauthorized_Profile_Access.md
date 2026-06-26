# BR-002: Unauthorized user can access Profile page via direct URL

## Summary

An unauthorized user can access the Profile page by navigating directly to the `/profile` URL without authentication.

---

## Environment

- Environment: Production
- Browser: Google Chrome
- OS: macOS Sequoia 15.6.1

---

## Preconditions

- User is logged out.
- Browser cookies/session have been cleared.

---

## Steps to Reproduce

1. Open the application.
2. Ensure the user is not authenticated.
3. Enter the following URL directly in the browser:
   ```
   /profile
   ```
4. Press **Enter**.

---

## Actual Result

The Profile page is displayed even though the user is not authenticated.

---

## Expected Result

The application should deny access to the Profile page and redirect the user to the Login page (or Home page), or display an **Unauthorized (401/403)** response.

---

## Severity

High

---

## Priority

High

---

## Attachment

Screen recording / Screenshot
