Manual Testing Portfolio: SauceDemo.com

📌 Project Overview

This project demonstrates manual functional testing of the [SauceDemo](https://www.saucedemo.com/) e-commerce platform. The focus was on verifying core user flows, including authentication, product interaction, and the checkout process, using various user personas.

🧪 Scopes of Testing

* Authentication: Login/Logout functionality.  
* Inventory: Browsing products and "Add to Cart" features.  
* Cart Management: Validating items and removing products.  
* Checkout Workflow: Form validation and order finalization.

👤 Tested User Personas

The testing focused on how the system handles different account types:

* standard\_user: Verified the "Happy Path" (standard functional flow).  
* locked\_out\_user: Validated error handling and access restriction.  
* problem\_user: Identified UI/UX bugs and functional glitches specific to this profile.

📄 Test Deliverables

The following artifacts were created during testing:

1. Test Plan: Defining the strategy, scope, and environment.  
2. Test Cases: Detailed steps for Login, Cart, and Checkout scenarios (including Expected vs. Actual results).  
3. Bug Reports: Documentation of issues found (especially under the problem\_user profile), including severity and steps to reproduce.

🛠 Tools Used

* Browser: Google Chrome / Mozilla Firefox  
* DevTools: For inspecting elements and checking console errors.  
* Documentation: Google Sheets / MS Excel (or Jira/Trello if applicable).

🚀 Key Results

* Successfully identified that the locked\_out\_user is correctly prevented from entering the site.  
* Documented inconsistent image rendering and broken "Add to Cart" buttons for the problem\_user.  
* Confirmed a seamless checkout flow for the standard\_user.