

| Test ID | Title | Precondition | Steps | Expected Result |
| :---- | :---- | :---- | :---- | :---- |
| TC-LOGIN-001 | Valid Login | User is on login page | 1\. Enter valid username 2\. Enter valid password 3\. Click Login | User is redirected to inventory page |
| TC-LOGIN-002 | Invalid Password | User is on login page | 1\. Enter valid username 2\. Enter invalid password 3\. Click Login | Error message displayed |
| TC-LOGIN-003 | Empty Fields | User is on login page | 1\. Leave fields empty 2\. Click Login | Error message: Username is required |
| TC-LOGIN-004 | Locked User | User is on login page | 1\. Enter locked\_out\_user 2\. Enter password 3\. Click Login | Error message: user locked |
| TC-CART-001 | Add to Cart | User logged in | 1\. Click Add to cart | Item appears in cart |
| TC-CART-002 | Remove from Cart | Item in cart | 1\. Click Remove | Item removed |
| TC-CART-003 | Cart Persistence | Item in cart | 1\. Refresh page | Item still in cart |
| TC-CART-004 | Open Cart | User logged in | 1\. Click cart icon | Cart page opens |
| TC-CHECKOUT-001 | Successful Checkout | Item in cart | 1\. Go to cart 2\. Click Checkout 3\. Fill form 4\. Continue 5\. Finish | Order confirmation displayed |
| TC-CHECKOUT-002 | Missing Info | On checkout page | 1\. Leave fields empty 2\. Click Continue | Error message displayed |
| TC-CHECKOUT-003 | Cancel Checkout | Checkout started | 1\. Click Cancel | Return to cart |
| TC-CHECKOUT-004 | Verify Total Price | Multiple items in cart | 1\. Go to overview | Total price correct |

