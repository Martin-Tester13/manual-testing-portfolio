**Bug Report – Unable to Remove Sauce Labs Backpack from Cart**

**Project:** SauceDemo  
 **Environment:** Web Application  
 **Tester:** Manual QA Tester Portfolio Sample  
 **Date:** 2026-05-09

## **Bug Summary**

The "Sauce Labs Backpack" item cannot be removed from the shopping cart after being added.

## **Bug Details**

| Bug ID | SD-CART-002 |
| :---- | :---- |
| Title | Unable 	to remove Sauce Labs Backpack from cart |
| Severity | High |
| Priority | High |
| Status | Open |
| Module | Cart / Inventory |
| Environment | Firefox Browser / SauceDemo Test Environment |
| Test Type | Manual Functional Testing |
| Affected User | problem\_user |

## **Preconditions**

* User is logged into SauceDemo using the "problem\_user" account.  
* User is on the inventory page.

## **Steps to Reproduce**

1. Open the SauceDemo application.  
2. Log in using the username "problem\_user".  
3. Add the item "Sauce Labs Backpack" to the cart.  
4. Open the shopping cart.  
5. Click the "Remove" 	button for the "Sauce Labs Backpack" item.

## **Expected Result**

The selected item should be removed from the cart after clicking the "Remove" button.

## **Actual Result**

The "Sauce Labs Backpack" item remains in the cart and is not removed after clicking the "Remove" button.

## **Impact**

Users cannot properly manage cart contents, which affects checkout preparation and overall shopping functionality.

## **Suggested Fix**

Investigate cart item removal functionality and ensure the "Remove" button correctly updates the cart state for the affected item.

