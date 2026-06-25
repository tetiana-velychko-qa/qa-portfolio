## BUG-002 — Password Reset Link Returns "Not Found" Page

**Severity:** High  
**Priority:** High  
**Status:** Closed  

---

### Preconditions
- User account already exists
- Password reset email was triggered (token retrieved via Docker logs)

### Environment
- OS: macOS Sequoia 15.7.7
- Browser: Chrome 149
- App: localhost:5173 (local dev build, Docker)

### Steps to Reproduce
1. Trigger "Forgot password" flow
2. Retrieve reset token from Docker logs
3. Navigate to `localhost:5173/reset-password?token=<token>` in the browser

### Actual Result
Page displays "Not Found" — the route does not exist in the frontend.

### Expected Result
User should see the password reset form to enter a new password.

### Root Cause (identified)
Route `/reset-password` is missing in `src/main.tsx` despite the 
`ResetPassword` component being implemented.

### Attachments
<!-- скрін сюди -->
