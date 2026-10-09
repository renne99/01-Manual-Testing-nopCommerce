# Test Summary - User Registration

Total test cases: 2<br>
Passed: 2<br>
Failed: 0

Failures:

* None – all executed test cases passed.

Defects found outside test cases:

* BUG-001 – Weak password is accepted during registration (found during exploratory testing)
* BUG-002 – Account is activated without email verification (found during exploratory testing)

Observations:

* Registration works with valid details.
* Mandatory field validation works as expected.
* Password strength and email verification are not enforced.

Recommendations: Developer to enforce password rules and email verification; QA to retest after fix.

Tester: Asisipho Nosasa