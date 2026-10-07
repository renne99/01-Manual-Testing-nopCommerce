# Use Case: UC-07 — Add to Wishlist

**Use Case ID:** UC-07<br>
**Name:** Add to Wishlist<br>
**Actor:** Registered User (Customer)<br>
**Preconditions:** User is logged in and viewing a product.<br>

**Basic Flow:**

1. User clicks "Add to wishlist" on a product
2. System adds the product to the user's wishlist
3. User opens the wishlist page to review saved items

**Alternate Flow:**

- User adds the same product to the wishlist twice -> system currently allows duplicate entries (see BUG-003)

**Exception Flow:**

- User is not logged in -> system should redirect to login before allowing the wishlist action

**Postcondition:** Product appears in the user's wishlist for later viewing or purchase.