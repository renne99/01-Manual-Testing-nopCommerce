# Use Case: UC-03 — Product Search

**Use Case ID:** UC-03<br>
**Name:** Product Search<br>
**Actor:** Guest or Registered User<br>
**Preconditions:** User is on any page of the site with the search bar visible.<br>

**Basic Flow:**

1. User clicks the search bar
2. User types a product name that exists in the catalogue
3. User clicks the search icon or presses Enter
4. System displays a list of matching products

**Alternate Flow:**

- Search term matches no products -> system shows "No products were found that matched your criteria"

**Exception Flow:**

- Search term left empty -> system shows the full product catalogue or a validation message

**Postcondition:** Matching products are displayed, or the user is clearly told none were found.