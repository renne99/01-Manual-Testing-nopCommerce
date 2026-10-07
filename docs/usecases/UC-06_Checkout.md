# Use Case: UC-06 — Checkout

**Use Case ID:** UC-06<br>
**Name:** Checkout<br>
**Actor:** Registered User (Customer)<br>
**Preconditions:** User is logged in and has at least one item in the cart.<br>

**Basic Flow:**

1. User opens the cart page
2. User clicks "Checkout"
3. User confirms or enters a billing/shipping address
4. User selects a shipping method
5. User selects a payment method
6. User confirms the order
7. System displays an order confirmation

**Alternate Flow:**

- Required address field left empty -> system shows a validation error and blocks progress to the next step

**Exception Flow:**

- Cart becomes empty mid-checkout (e.g. opened in another tab) -> system redirects back to an empty cart page

**Postcondition:** An order is created and the user receives an order confirmation.