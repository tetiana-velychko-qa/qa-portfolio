## BUG-003 — Password Reset Email Is Not Delivered to User

**Severity:** High  
**Priority:** High  
**Status:** Open  

---

### Preconditions
- User account already exists with a valid email address
- "Forgot password" flow is initiated

### Environment
- OS: macOS Sequoia 15.7.7
- Browser: Chrome 149
- App: localhost:5173 (local dev build, Docker)

### Steps to Reproduce
1. Open Login page
2. Click "Forgot password"
3. Enter registered email address
4. Click "Send reset link"
5. Check inbox of the provided email address

### Actual Result
UI displays success message: "If your email exists, we will send you a message."
No email is received in the inbox. Reset token is only accessible via Docker logs.

### Expected Result
User should receive a password reset email with a valid reset link.

### Attachments
<img width="1280" height="713" alt="Image" src="https://github.com/user-attachments/assets/b1da3733-68c1-4820-91e5-859e995b13ca" />
