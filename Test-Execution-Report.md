# Test Execution Report

## 1. Project Information

| Field | Details |
|---|---|
| Project Name | ShopSphere – Manual Testing |
| Application Under Test | Practice Software Testing |
| Application URL | https://practicesoftwaretesting.com |
| Testing Type | Manual Testing |
| Testing Approach | Functional Testing |
| Tester | Adarsh Kumar Gupta |
| Test Environment | Web Browser |
| Operating System | Ubuntu Linux |
| Browser | Mozilla Firefox |
| Execution Date | 25/11/2026 |
| Overall Status | Completed – results recorded |

## 2. Testing Objectives

The objective of this testing activity is to verify the functionality of the application and identify defects through manual testing.

The testing focuses on the following modules:

1. Login and Registration
2. Product Search
3. Shopping Cart
4. Coupon Application
5. Checkout and Payment


## 3. Modules Tested

| Module | Testing Scope | Execution Status |
|---|---|---|
| Login and Registration | Registration, login, mandatory fields, password validation | Executed |
| Product Search | Existing products, non-existing products, case sensitivity, product details | Executed |
| Shopping Cart | Add, remove, quantity changes, stock validation, total calculation | Executed |
| Coupon Application | Valid/invalid coupons and discount calculation | Blocked |
| Checkout and Payment | Address validation, payment, failure handling, duplicate order prevention | Executed |

## 4. Test Execution Summary

The project contains 42 test cases. Based on the updated counts supplied, 31 passed, 7 failed, and 4 were blocked.

| Metric | Count |
|---|---:|
| Total Test Cases | 42 |
| Executed Test Cases (Pass + Fail) | 38 |
| Passed | 31 |
| Failed | 7 |
| Blocked | 4 |
| Not Run | 0 |

**Pass Percentage**

Pass Percentage = (Passed Test Cases / Executed Test Cases) × 100

Pass Percentage = (31 / 38) × 100 = **81.58%**

Blocked test cases are excluded from the pass-percentage calculation because they were not executed.

## 5. Module-wise Execution Results

| Module | Total Test Cases | Passed | Failed | Blocked | Not Run |
|---|---:|---:|---:|---:|---:|
| Login and Registration | 14 | 11 | 3 | 0 | 0 |
| Product Search | 8 | 7 | 1 | 0 | 0 |
| Shopping Cart | 8 | 7 | 1 | 0 | 0 |
| Coupon Application | 4 | 0 | 0 | 4 | 0 |
| Checkout and Payment | 7 | 6 | 1 | 0 | 0 |
| Additional test case (module/ID to confirm) | 1 | 0 | 1 | 0 | 0 |
| **Total** | **42** | **31** | **7** | **4** | **0** |


## 6. Defects Identified

A total of **7 failed test cases / reported issues** are recorded in the updated execution figures.

| Metric | Count |
|---|---:|
| Failed test cases | 7 |
| Bug reports | 7 (as reported; reconcile with Bug-Reports.xlsx) |
| Confirmed defects | Update after verifying each issue |

A failed test case should be recorded as a confirmed defect only when the expected behavior is supported by the assignment requirements or an agreed requirement, and the issue has been reproduced.

Refer to `Bug-Reports.xlsx` for the individual bug IDs, titles, reproduction steps, expected and actual results, severity, priority, and evidence.



## 7. Conclusion

Manual functional testing was performed on the Practice Software Testing application across the five selected modules.

A total of 42 test cases were recorded: 31 passed, 7 failed, and 4 were blocked. The resulting pass percentage for executed test cases is **81.58%**.

The failed cases should be reviewed against the assignment requirements, and only reproducible issues with a valid expected result should be treated as confirmed defects. Coupon test cases remain blocked and should be revisited if the functionality becomes available.

**Overall Status:** Execution completed; defect verification may remain pending.

**Prepared By:** Adarsh Kumar Gupta  
**Date:** 25/11/2026
