## What is a Cookie?
A cookie is small data stored in the user's browser.  
It is created by the server and sent with every request.

### Uses of Cookies
- Remember logged-in users
- Store preferences (theme, language)
- Track sessions

### Example
When you log in:
- Server sends a cookie to your browser
- Browser stores it
- Website recognizes you on next visit

---

## Types of Cookies
- **Session Cookie** – deleted when browser closes
- **Persistent Cookie** – stored for long time
- **Secure Cookie** – sent only over HTTPS
- **HttpOnly Cookie** – not accessible via JavaScript

---

## What is a Session?
A session is stored on the **server**.  
It tracks the user after login using a **Session ID**.

### How Sessions Work
1. User logs in
2. Server creates a session
3. Session ID is sent as a cookie
4. Browser sends Session ID with every request
5. Server validates the user

---

## Cookie vs Session

| Cookie | Session |
|------|--------|
| Stored in browser | Stored on server |
| Less secure | More secure |
| Can be modified | Cannot be modified |
| Small data | Larger data |

---

## Why Cookies & Sessions Matter in Cybersecurity
- Weak cookies can lead to **session hijacking**
- Stolen session ID = attacker logs in as victim
- Used in attacks like:
  - Session Hijacking
  - XSS
  - CSRF

---

## Security Best Practices
- Always use HTTPS
- Use HttpOnly cookies
- Regenerate session after login
- Destroy session on logout

---

## What I Learned
Cookies and sessions are core to authentication.
Understanding them is essential for web security testing.
