# Test Plan- E-Commerce Website

## 1. Introduction
This Test Plan defines the testing approach, objectives, entry and exit criteria, and risks associated with the manual testing of the nopCommerce e-commerce website. For the full list of features and expected behaviour under test, see [Requirements.md](../requirements.md).

## 2. Objectives
- Verify that the application's core functionality operates as expected.
- Identify functional defects and unexpected behaviour.
- Validate the key customer workflows of the e-commerce application.
- Verify that invalid and unexpected inputs are handled appropriately.
- Ensure that defects are documented with sufficient information for investigation.

## 3. Scope
This Test Plan covers the functional requirements listed in [Requirements.md](../requirements.md) (sections 2 and 3): User Registration, Login/Logout, Product Search, Product Details, Shopping Cart, Checkout, and Wishlist.

Out of scope items are the same as listed in Requirements.md section 2 (performance testing, API testing, payment gateway certification, etc.).

## 4. Test Strategy
Testing will be performed using a combination of functional, negative, exploratory and scenario-based testing techniques. The testing will focus on validating the behaviour of the application's key customer workflows.

Test cases will be designed around positive and negative scenarios to verify expected functionality as well as the application's response to invalid or unexpected input.

Functional testing will be used to verify that application features perform their intended functions. Negative testing will be used to verify that invalid input and incorrect user actions are handled appropriately.

Exploratory testing will also be performed to identify unexpected behaviour that may not be covered by predefined test cases.

Defects identified during execution will be documented with steps to reproduce, expected results, actual results, severity and priority.

### 4.1 Test Coverage
| Test Area | Existing Coverage |
|---|---|
| Registration | TC_01, TC_02 |
| Login | TC_03 |
| Product Search | TC_04, TC_05 |
| Shopping Cart | TC_06, TC_07 |
| Checkout | TC_08 |
| Logout | TC_09 |
| Wishlist | Bug003 |
| Password Validation | Bug001 |
| Email Verification | Bug002 |

## 5. Entry and Exit Criteria

### 5.1 Entry Criteria
- The nopCommerce application is accessible.
- The required test environment is available.
- The application functionality under test is available.
- Test data required for execution is available.
- Test scenarios and test cases have been prepared.
- The tester understands the functionality being tested.
- The browser and required testing environment are operational.

### 5.2 Exit Criteria
- All planned test cases have been executed.
- Test results have been recorded.
- Identified defects have been documented.
- Critical testing areas have been covered.
- Failed test cases have been investigated.
- Required retesting has been completed.
- Regression testing has been performed where applicable.
- Test results have been documented.
- Outstanding risks and defects have been identified.

## 6. Risk Register
| ID | Risk | Impact | Likelihood | Mitigation |
|---|---|---|---|---|
| R-001 | Demo application becomes unavailable | High | Medium | Verify application availability before test execution and resume testing when available |
| R-002 | Changes to the demo application affect existing test cases | Medium | Medium | Review affected test cases and update them when functionality changes |
| R-003 | Test data becomes invalid or unavailable | Medium | Medium | Maintain appropriate test data for required scenarios |
| R-004 | Browser compatibility issues affect test execution | Medium | Low | Execute relevant tests using supported browsers |
| R-005 | Defects prevent further testing of dependent functionality | High | Medium | Log the blocking defect and continue testing independent functionality where possible |
