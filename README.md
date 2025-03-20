# Manual, automation Exercise Website and API Testing Project

## Team

* Menna-Allah abdalmoaty
* Ahmed Mohamed
* Momen Maged
* Doha Abdelazeim
* Ahmed Salah
* Abd Al-Rahman Nageh

## Project Overview

This project focuses on testing the Automation Exercise website and its associated APIs to ensure the core functionalities are working as expected.

## Testing Scope

The testing encompasses the following core functionalities:

* User registration
* Login
* Product Browse
* Shopping cart
* Checkout
* Contact form
* Subscription features
* Product reviews
* Invoice downloading
* Website navigation and scroll functionality
* API testing for product lists, brands, search, login verification, user account management, and user details.

## Identified Risks

* Browser compatibility issues.
* API response time fluctuations.
* Potential for unexpected user input errors.

## Key Performance Indicators (KPIs)

* Bug detection rate.
* Test coverage percentage.
* API response time (average).

## Test Cases

### Website Test Cases

1.  Register User
2.  Login User with correct email and password
3.  Login User with incorrect email and password
4.  Logout User
5.  Register User with existing email
6.  Contact Us Form
7.  Verify Test Cases Page
8.  Verify All Products and product detail page
9.  Search Product
10. Verify Subscription in home page
11. Verify Subscription in Cart page
12. Add Products in Cart
13. Verify Product quantity in Cart
14. Place Order: Register while Checkout
15. Place Order: Register before Checkout
16. Place Order: Login before Checkout
17. Remove Products From Cart
18. View Category Products
19. View & Cart Brand Products
20. Search Products and Verify Cart After Login
21. Add review on product
22. Add to cart from Recommended items
23. Verify address details in checkout page
24. Download Invoice after purchase order
25. Verify Scroll Up using 'Arrow' button and Scroll Down functionality
26. Verify Scroll Up without 'Arrow' button and Scroll Down functionality.1

### API Test Cases

1.  **API 1:** Get All Products List (GET, 200)
2.  **API 2:** POST To All Products List (POST, 405)
3.  **API 3:** Get All Brands List (GET, 200)
4.  **API 4:** PUT To All Brands List (PUT, 405)
5.  **API 5:** POST To Search Product (POST, 200, search\_product parameter)
6.  **API 6:** POST To Search Product without search\_product parameter (POST, 400)
7.  **API 7:** POST To Verify Login with valid details (POST, 200, email, password)
8.  **API 8:** POST To Verify Login without email parameter (POST, 400, password)
9.  **API 9:** DELETE To Verify Login (DELETE, 405)
10. **API 10:** POST To Verify Login with invalid details (POST, 404, email, password)
11. **API 11:** POST To Create/Register User Account (POST, 201, all required user parameters)
12. **API 12:** DELETE METHOD To Delete User Account (DELETE, 200, email, password)
13. **API 13:** PUT METHOD To Update User Account (PUT, 200, all required user parameters)
14. **API 14:** GET user account detail by email (GET, 200, email)

## Non-Functional Requirements

* **Usability:** The website should be user-friendly.
* **Reliability:** The website and APIs should function consistently.
* **Performance:** The website and APIs should load and respond quickly.
* **Compatibility:** The website should be compatible with major web browsers (Chrome, Firefox, Edge).

## User Stories

* As a new user, I want to register an account to make purchases.
* As a returning user, I want to log in with my credentials.
* As a user, I want to browse products by category and brand.
* As a user, I want to add products to my cart and view my cart before checkout.
* As a user, I want to complete the checkout process and place an order.
* As a user, I want to search for products by name.
* As a user, I want to subscribe to a newsletter.
* As a user, I want to contact customer support through a contact form.
* As a user, I want to add reviews to products.
* As a user, I want to download an invoice of my purchase.
* As a user, I want the page to scroll up and down.
