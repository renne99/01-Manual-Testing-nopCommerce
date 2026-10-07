# Use Case: UC-05 — Add to Cart and Update Quantity

**Use Case ID:** UC-05<br>
**Name:** Add to Cart and Update Quantity<br>
**Actor:** Guest or Registered User<br>
**Preconditions:** User is on a product details page for an in-stock item.<br>

**Basic Flow:**

1. User selects a quantity
2. User clicks "Add to cart"
3. System adds the item and shows a confirmation message
4. User opens the cart page
5. User updates the quantity and clicks the cart's update/refresh icon
6. System recalculates the item subtotal and cart total

**Alternate Flow:**

- Quantity entered as 0 or a negative number -> system should reject the update and show a validation message

**Exception Flow:**

- Item goes out of stock after being added -> system shows a stock warning at checkout

**Postcondition:** Cart reflects the correct products, quantities, and total price.