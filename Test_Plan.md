Appliaction: SauceDemo

1. Objective

	The objective of this testing is to verify core functionalities of the web application:

* User login  
* Shopping cart functionality  
* Checkout process

2. Scope  
   In scope:  
* Login page  
* Product inventory  
* Add/remove items from cart  
* Checkout process

	Out of scope:

* Performance testing  
* Security testing  
* API testing

3. Testing Strategy  
   Testing will be executing manually with:  
* happy path  
* error scenario  
* simply explorative testing

4. Test Environment  
* Browser: Google Chrome, Firefox  
* OS: Linux mint 22.3  
* Device: Laptop  
* Internet: Stable connection

5. Test Data  
   Test accounts used:  
* standard\_user \- valid user  
* locked\_out\_user \- blocked user

6. Main Test Scenarios  
   Login  
* Login with valid credentials  
* Login with invalid credentials  
* Login with empty fields

	Cart:

* Add product to cart  
* Remove product from cart  
* Verify cart item count

	Checkout

* Enter user information  
* Review order details  
* Complete the purchase

7. Entry/Exit Criteria  
   Entry Criteria:  
* Application is accessible  
* Test accounts are working

	Exit Criteria:

* All main scenarios are executed  
* Critical bugs are documented

8. Risks  
* Application instability  
* Limited test data  
* Begginer-level experience

9. Deliverables  
* Test scenarios  
* Bug reports  
* Short test summary