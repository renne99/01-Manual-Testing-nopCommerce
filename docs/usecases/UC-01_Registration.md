# Use Case: UC-01 — User Registration

**Use Case ID:** UC-01<br>
**Name:** User Registration<br>
**Actor:** Guest User (New Customer)<br>
**Preconditions:** User is on the nopCommerce demo site and does not have an existing account.<br>

**Basic Flow:**

1. Open https://demo.nopcommerce.com/
2. Click "Register"
3. User enters first name, last name, email, and password
4. User clicks "Register"
5. System creates the account and logs the user in

**Alternate Flow:**

- Weak password entered -> system should prompt for a stronger password (see BUG-001)

**Exception Flow:**

- Email already registered -> system shows "The specified email already exists" error

**Postcondition:** A new customer account exists and the user is logged in.