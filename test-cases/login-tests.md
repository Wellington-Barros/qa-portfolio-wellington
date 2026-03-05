# Login Test Cases

## Test Case 1 - Valid Login

**Test ID:** TC_LOGIN_001  
**Scenario:** User logs in with valid credentials  

**Steps:**
1. Navigate to login page
2. Enter valid email
3. Enter valid password
4. Click login

**Expected Result:**  
User is successfully logged into the system.


---

## Test Case 2 - Invalid Password

**Test ID:** TC_LOGIN_002  
**Scenario:** User enters incorrect password

**Steps:**
1. Navigate to login page
2. Enter valid email
3. Enter incorrect password
4. Click login

**Expected Result:**  
System displays an error message: "Invalid credentials".


---

## Test Case 3 - Empty Fields

**Test ID:** TC_LOGIN_003  
**Scenario:** User tries to login with empty fields

**Steps:**
1. Navigate to login page
2. Leave email empty
3. Leave password empty
4. Click login

**Expected Result:**  
System should display validation message requiring fields to be filled.
