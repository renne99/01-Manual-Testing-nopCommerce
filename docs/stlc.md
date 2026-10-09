# Software Testing Life Cycle (STLC) – nopCommerce Testing Project

This document describes the STLC phases followed in this QA project.


## 1. Requirement Analysis

### Activities:

* Studied core features of nopCommerce (Registration, Login, Search, Cart, Checkout, Wishlist, etc.).
* Identified what can be tested and what is not available.
* Understood UI behaviour, validations, and user flows.

### Deliverables:

* Requirements Document
* List of testable features


## 2. Test Planning

### Activities:

* Decided scope of testing (manual functional testing).
* Defined resources: tester, Chrome browser, nopCommerce demo site.
* Selected test techniques (functional, negative, exploratory, and scenario-based testing).
* Estimated number of test cases.

### Deliverables:

* Test Plan
* Test Strategy decisions
* Effort estimation


## 3. Test Case Design

### Activities:

* Created test scenarios and detailed test cases for:
   * User Registration
   * Login / Logout
   * Product Search
   * Product Details
   * Add to Cart & Update Quantity
   * Checkout
   * Wishlist

### Deliverables:

* Test scenarios (TS_01 to TS_10)
* Test cases (TC-01 to TC-09)
* Use cases (UC-01 to UC-07)


## 4. Test Environment Setup

### Activities:

* Prepared Chrome browser on Windows 11 for testing.
* Created folder structure with:
   * evidence/screenshots
   * .md documentation
* Verified website availability.

### Deliverables:

* Test Environment Checklist
* Ready test workspace


## 5. Test Execution

### Activities:

* Executed all test cases manually.
* Marked each as Pass / Fail.
* Collected screenshots for evidence.
* Logged issues found.

### Deliverables:

* Executed Test Case files
* Evidence screenshots


## 6. Defect Reporting & Tracking

### Activities:

* Reported bugs using the bug report template:
   * BUG-001 – Weak password is accepted during registration
   * BUG-002 – Account is activated without email verification
   * BUG-003 – Duplicate products allowed in the wishlist

### Deliverables:

* Individual Bug Reports
* Failed Test Case references


## 7. Test Closure

### Activities:

* Prepared a Test Summary Report covering all tested modules.
* Ensured all high-priority bugs are documented.
* Organized final documentation for submission.

### Deliverables:

* Test Summary Report
* Observations / Recommendations


**Prepared By:** Asisipho Nosasa<br>
**Date:** 07-10-2026
