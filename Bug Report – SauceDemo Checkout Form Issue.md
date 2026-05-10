**Bug Report – SauceDemo Checkout Form Issue**

**Project:** SauceDemo  
 **Environment:** Web Application  
 **Tester:** Manual QA Tester Portfolio Sample  
 **Date:** 2026-05-09

## **Bug Summary**

The "Last Name" field in the checkout form cannot be filled when logged in as the "problem\_user" account. This prevents successful completion of the checkout process.

## **Bug Details**

| Bug ID | SD-CHK-001		 |
| :---- | :---- |
| Title 		 | Last Name field cannot be filled during checkout for problem\_user |
| Severity		 | High |
| Priority | High |
| Status | Open |
| Module | Checkout – Your Information |
| Environment | Firefox Browser / SauceDemo Test Environment |
| Test Type | Manual Functional Testing |
| User Account | problem\_user |

## **Preconditions**

* User is logged into SauceDemo using the "problem\_user" account.  
* At least one product is added to the cart.  
* User navigates to the checkout page.

## **Steps to Reproduce**

1. Open the SauceDemo application.  
2. Log in using the username "problem\_user".  
3. Add any product to the cart.  
4. Open the cart and click "Checkout".  
5. Try to enter text into the "Last Name" field.

## **Expected Result**

The user should be able to enter text into the "Last Name" field and continue the checkout process successfully.

## **Actual Result**

The "Last Name" field does not accept input, preventing the user from completing the checkout form.

## **Impact**

Users logged in as "problem\_user" cannot complete purchases, which blocks the checkout workflow and affects core functionality testing.

## **Suggested Fix**

Investigate input field handling and validation logic for the "problem\_user" account during checkout. Ensure the field accepts standard keyboard input and form events are processed correctly.

