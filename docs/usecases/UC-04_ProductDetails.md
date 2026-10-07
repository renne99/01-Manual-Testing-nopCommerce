# Use Case: UC-04 — View Product Details

**Use Case ID:** UC-04<br>
**Name:** View Product Details<br>
**Actor:** Guest or Registered User<br>
**Preconditions:** User has located a product via search or category browsing.<br>

**Basic Flow:**

1. User clicks on a product name or image
2. System opens the product details page
3. User reviews price, description, and available options (size/colour, if any)

**Alternate Flow:**

- Product is out of stock -> page shows an out-of-stock message instead of the Add to Cart button

**Exception Flow:**

- Product page fails to load -> system shows a 404 or error page

**Postcondition:** User has enough information to decide whether to add the product to their cart.