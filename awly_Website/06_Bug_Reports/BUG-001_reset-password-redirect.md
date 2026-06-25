## Forgot Password redirects to Sign In page

**ID:** BUG-001  
**Severity:** High  
**Priority:** High  
**Status:** Open

---

### Preconditions
- User account already exists
- App is running locally (Docker)

### Environment
- OS: macOS 
- Browser: Chrome 125
- App version: local dev build

---

### Steps to Reproduce
1. Open Login page
2. Click "Forgot password"
3. Observe navigation behavior

### Actual Result
User is redirected to the Sign In page instead of the password reset flow/page.

### Expected Result
User should be redirected to `/reset-password` page to continue the password recovery flow.

### Root Cause (identified)
Route `/reset-password` is missing in `src/main.tsx` despite the component being implemented.

---

### Attachments
<!-- відео сюди -->
