# Use Case: UC-02 — Login and Logout

**Use Case ID:** UC-02<br>
**Name:** Login and Logout<br>
**Actor:** Registered User (Customer)<br>
**Preconditions:** User has an existing account and is on the login page.<br>

**Basic Flow:**

1. Open https://demo.nopcommerce.com/login
2. User enters a registered email and password
3. User clicks "Log in"
4. System validates the credentials and redirects to the account/home page
5. User clicks "Log out" and is returned to the home page

**Alternate Flow:**

- Invalid credentials entered -> system shows "Login was unsuccessful" error message

**Exception Flow:**

- Server/site unavailable -> browser shows a connection/service error instead of the login page

**Postcondition:** User session is either active (logged in) or fully ended (logged out).