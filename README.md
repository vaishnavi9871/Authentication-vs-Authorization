# Authentication-vs-Authorization

✅ 1. Authentication (AuthN)

👉 Who are you?

Authentication is about verifying identity.

✔ Examples:
Login with username/password
OTP verification
Login with Google

✔ Real-world example:
You enter email + password
Server checks → valid?

✔ If yes → you are authenticated
Authentication-> Verify identity-> Who are you? -> First step -> Login	-> 401 Unauthorized


✅ 2. Authorization (AuthZ)

👉 What are you allowed to do?

Authorization happens after authentication.

✔ Examples:
Admin can delete users
Normal user cannot access admin panel

✔ Real-world example:
You are logged in ✅
Try to access /admin
❌ Access denied → not authorized
🔥 Simple Analogy (Easy to remember)

Think of a movie theater 🎬

Authentication → Showing your ticket at entry
✔ “Are you a valid customer?”
Authorization → Seat access
✔ “Can you sit in VIP or regular?”
⚡ Key Differences
Authorization->Check permissions->What can you do?->After login->Access control->403 Forbidden


🔥 HTTP Status Code Mapping (IMPORTANT)
401 Unauthorized
👉 Not logged in / invalid token
👉 Authentication failed
403 Forbidden
👉 Logged in but no permission
👉 Authorization failed



👉 Authentication verifies identity, Authorization determines access.
