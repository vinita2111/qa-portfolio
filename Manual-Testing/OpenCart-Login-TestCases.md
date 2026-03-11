
# OpenCart – Registration Functionality Test Cases

Application URL: https://demo.opencart.com

---

## Test Case 1: Valid Registration

Test Case ID: TC_Reg_001  
Description: Verify user can register with valid details  
Precondition: User not registered with this email  

Steps:
1. Navigate to Registration page  
2. Enter valid First Name, Last Name  
3. Enter valid Email  
4. Enter Password and Confirm Password  
5. Agree to Terms & Conditions  
6. Click Continue  

Expected Result:  
User should see “Your Account Has Been Created!” message.

---

## Test Case 2: Registration with Existing Email

Test Case ID: TC_Reg_002  
Description: Verify error message when registering with already used email  

Steps:
1. Navigate to Registration page  
2. Enter valid details with an already registered email  
3. Click Continue  

Expected Result:  
Proper error message should be displayed.

---

## Test Case 3: Mandatory Fields Validation

Test Case ID: TC_Reg_003  
Description: Verify validation messages for empty mandatory fields  

Steps:
1. Navigate to Registration page  
2. Leave First Name, Last Name, Email, Password empty  
3. Click Continue  

Expected Result:  
Validation messages should appear for all mandatory fields.

# OpenCart – Login Functionality Test Cases

Application URL:
https://demo.opencart.com

---

## Test Case 1: Valid Login

Test Case ID: TC_Login_001  
Description: Verify user can login with valid credentials  
Precondition: User account already registered  

Steps:
1. Navigate to Login page  
2. Enter valid email  
3. Enter valid password  
4. Click Login button  

Expected Result:
User should successfully login and be redirected to My Account page.

---

## Test Case 2: Invalid Password

Test Case ID: TC_Login_002  
Description: Verify error message for incorrect password  

Steps:
1. Navigate to Login page  
2. Enter valid email  
3. Enter invalid password  
4. Click Login button  

Expected Result:
Proper error message should be displayed.

---

## Test Case 3: Empty Fields

Test Case ID: TC_Login_003  
Description: Verify validation for empty email and password  

Steps:
1. Navigate to Login page  
2. Leave email blank  
3. Leave password blank  
4. Click Login button  

Expected Result:
Validation message should be displayed.

# OpenCart – Add to Cart Functionality Test Cases

Application URL:
https://demo.opencart.com

---

## Test Case 1: Add Product to Cart

Test Case ID: TC_Cart_001  
Description: Verify user can add a product to the cart  

Steps:
1. Navigate to Home page  
2. Select any product  
3. Click "Add to Cart" button  

Expected Result:
Product should be successfully added to the shopping cart and cart count should update.

---

## Test Case 2: Add Multiple Products to Cart

Test Case ID: TC_Cart_002  
Description: Verify user can add multiple products to the cart  

Steps:
1. Navigate to Home page  
2. Select first product and click "Add to Cart"  
3. Select another product  
4. Click "Add to Cart"  

Expected Result:
Both products should appear in the shopping cart.

---

## Test Case 3: Add Same Product Multiple Times

Test Case ID: TC_Cart_003  
Description: Verify cart updates quantity when same product is added again  

Steps:
1. Navigate to Home page  
2. Select a product  
3. Click "Add to Cart" twice  

Expected Result:
Cart should show the product with updated quantity.

# OpenCart – Remove Product From Cart Test Cases

Application URL:
https://demo.opencart.com

---

## Test Case 1: Remove Product From Cart

Test Case ID: TC_Cart_004  
Description: Verify user can remove a product from the shopping cart  

Precondition:
Product is already added to the cart.

Steps:
1. Navigate to the Shopping Cart page  
2. Locate the added product  
3. Click the "Remove" or "Delete" icon next to the product  

Expected Result:
Product should be removed from the shopping cart and cart should update.

---

## Test Case 2: Remove Product When Multiple Items Exist

Test Case ID: TC_Cart_005  
Description: Verify user can remove one product when multiple products are in cart  

Precondition:
Multiple products are added to the cart.

Steps:
1. Navigate to Shopping Cart page  
2. Click remove icon for one product  

Expected Result:
Selected product should be removed while other products remain in the cart.

---

## Test Case 3: Cart Empty After Removing Last Product

Test Case ID: TC_Cart_006  
Description: Verify cart shows empty message after removing last product  

Precondition:
Only one product is present in the cart.

Steps:
1. Navigate to Shopping Cart  
2. Click remove icon for the product  

Expected Result:
Cart should show message like “Your shopping cart is empty”.
