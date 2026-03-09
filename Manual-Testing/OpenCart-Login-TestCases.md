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
