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
- OS: macOS Sequoia 15.7.7
- Browser: Chrome 149
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
(https://github.com/user-attachments/assets/aeaa1403-3ff6-4257-8480-8e7a70587d74)
