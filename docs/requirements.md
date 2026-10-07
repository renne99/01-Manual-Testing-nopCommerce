# Software Requirements – nopCommerce Website Testing Project

## 1. Introduction
This document defines the functional and non-functional requirements for testing the nopCommerce e-commerce demo website (https://demo.nopcommerce.com/). The purpose is to identify what features should be validated and what behaviour is expected from the system.

## 2. Scope

The scope of this QA project includes:

* User Registration
* User Login & Logout
* Product Search
* Product Details
* Shopping Cart
* Checkout
* Wishlist

Out of scope:

* Performance and load testing
* Security penetration testing
* API testing
* Database testing
* Mobile application testing
* Automated UI testing
* Payment gateway certification
* Infrastructure and server testing

## 3. Functional Requirements (FR)

**FR-01: User Registration**

* System must allow registration with a valid first name, last name, email, and password.
* System must validate mandatory fields and show an error when a required field is missing.
* System must enforce a minimum password strength *(currently not enforced — see BUG-001)*.

**FR-02: User Authentication (Login / Logout)**

* System must allow login using a registered email and password.
* System must show an error message for invalid credentials.
* Logout must end the session and redirect the user to the home page.

**FR-03: Product Search**

* User must be able to search for products by name.
* System must display matching results.
* System must show a clear "no results found" message when nothing matches.

**FR-04: Product Details**

* Clicking a product must open its product details page.
* Page must display the product name, price, description, and image.

**FR-05: Shopping Cart**

* User must be able to add one or more items to the cart.
* User must be able to update the quantity of an item in the cart.
* Cart subtotal and total must recalculate correctly after any change.

**FR-06: Checkout**

* User must provide a billing/shipping address.
* User must select a shipping method and a payment method.
* System must display an order confirmation once the order is placed.

**FR-07: Wishlist**

* User must be able to add a product to their wishlist.
* System must prevent duplicate entries for the same product *(currently not enforced — see BUG-003)*.

## 4. Non-Functional Requirements (NFR)

**NFR-01: Usability**

* Interface should be simple and easy to navigate.
* Buttons and links should be clearly visible and labelled.

**NFR-02: Performance**

* Pages should load within 3 seconds on a normal network connection.

**NFR-03: Compatibility**

* Website must work correctly on the latest version of Chrome and Firefox.

**NFR-04: Reliability**

* Website should not crash or lose cart contents during checkout navigation.

**NFR-05: Security**

* User must not be able to access account-specific pages (e.g. order history) without authentication.
* A registered account should require email verification before activation *(currently not enforced — see BUG-002)*.

## 5. Assumptions

* The payment process on the demo site is a sandbox and is not connected to a real payment gateway.
* The product catalogue is controlled by the shared public demo environment and may change over time.
* Because the demo site is public and shared with other testers, some test data (e.g. stock levels) may be altered outside of this project's control.

## 6. Risks

* Weak passwords are accepted during registration (Observed bug).
* Accounts are activated without email verification (Observed bug).
* The demo application may become unavailable or change without notice.
* Shared/public demo environment may produce inconsistent results between test runs.

---
**Prepared By:** Asisipho Nosasa<br>
**Date:** 07-10-2026
