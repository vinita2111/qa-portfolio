
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
