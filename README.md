# ShopSphere – Manual Testing Project

## Project Overview

This project focuses on manual functional testing of an e-commerce web application, **Practice Software Testing**.

The objective is to understand the application requirements, identify important test scenarios, prepare detailed test cases, execute them manually, and report genuine defects if found.

**Application URL:** https://practicesoftwaretesting.com

**Project Type:** Manual Software Testing  
**Testing Approach:** Functional Testing  
**Testing Method:** Manual Testing

---

## Project Objectives

- Understand the functional requirements of the application.
- Identify important test scenarios for each module.
- Prepare detailed and structured test cases.
- Execute test cases manually and record actual results.
- Identify and document genuine application defects.
- Prepare a test execution report summarizing the testing activities.

---

## Modules Covered

The testing scope is limited to the following five modules:

### 1. Login and Registration
- Register with valid and invalid details.
- Verify email uniqueness.
- Test login with valid and invalid credentials.
- Validate mandatory fields.
- Verify password length requirements.

### 2. Product Search
- Search for existing products.
- Search for non-existing products.
- Test uppercase and lowercase search inputs.
- Test search using special characters.
- Verify product details and prices.

### 3. Shopping Cart
- Add products to the cart.
- Remove products from the cart.
- Increase and decrease product quantities.
- Verify stock quantity restrictions.
- Validate cart subtotal and total calculations.

### 4. Coupon Application
- Apply a valid coupon.
- Apply an invalid or expired coupon.
- Verify minimum purchase requirements.
- Check whether multiple coupons can be applied.
- Validate discount calculations.

*Note: Coupon testing may be skipped if the application does not provide coupon functionality.*

### 5. Checkout and Payment
- Place an order using valid details.
- Verify checkout with missing address information.
- Test payment failure scenarios.
- Verify payment retry functionality.
- Check duplicate order prevention after repeated submission.

---

## Business Rules

The following business rules are considered during testing:

1. Email addresses must be unique.
2. Passwords must contain at least 8 characters.
3. Product quantity cannot exceed available stock.
4. Cart quantity cannot be zero or negative.
5. Only one coupon can be applied per order.
6. Coupon minimum purchase conditions must be satisfied.
7. The final order amount must include the correct discount.
8. Failed payments must not create successful orders.
9. Repeated payment submissions must not create duplicate orders.

---

## Project Structure

```text
ShopSphere-Manual-Testing/
│
├── README.md
│
├── Test-Scenarios.xlsx
│
├── Test-Cases.xlsx
│
├── Bug-Reports.xlsx
│
├── Screenshots/
│   └── README.md
│
└── Test-Execution-Report.md
```

---

## Testing Documentation

| File Name | Description |
|---|---|
| README.md | Project overview, objectives, scope, and testing approach |
| Test-Scenarios.xlsx | List of high-level test scenarios for all selected modules |
| Test-Cases.xlsx | Detailed test cases with preconditions, steps, test data, and expected results |
| Bug-Reports.xlsx | Record of genuine defects identified during testing |
| Screenshots/ | Supporting screenshots for failed test cases and reported defects |
| Test-Execution-Report.md | Summary of executed test cases and overall testing results |

---

## Test Case Execution Status

Each test case is assigned one of the following statuses:

| Status | Description |
|---|---|
| Pass | Actual result matches the expected result |
| Fail | Actual result differs from the expected result |
| Blocked | Test execution cannot be completed due to an application or environment limitation |
| Not Run | Test case has not yet been executed |

---


## Test Execution Summary

The final execution summary will be updated after completing manual testing.

| Metric | Result |
|---|---|
| Total Test Scenarios | Refer to Test-Scenarios.xlsx |
| Total Test Cases | Refer to Test-Cases.xlsx |
| Executed Test Cases | 41|
| Passed Test Cases | 31|
| Failed Test Cases | 6|
| Blocked Test Cases | 4|
| Not Run Test Cases | To be updated |
| Confirmed Defects | To be updated |

Refer to **Test-Execution-Report.md** for detailed execution results.

---


## Conclusion

This project demonstrates the practical implementation of manual software testing concepts, including requirement analysis, test scenario identification, test case preparation, test execution, defect reporting, and test result documentation.

The focus is on validating the application's functionality against the given requirements and business rules while maintaining accurate and genuine testing records.

---

**Project:** ShopSphere – Manual Testing  
**Application:** Practice Software Testing  
**Testing Approach:** Manual Functional Testing
