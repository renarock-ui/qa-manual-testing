# Login Form Validation – Test Cases

## TC-LOGIN-001: Validate email required field

**Description:**  
Verify that the login form does not allow submission when the email field is empty.

**Preconditions:**  
- User is on the login page

**Test Steps:**
1. Navigate to login page
2. Leave email field empty
3. Enter valid password
4. Click Submit button

**Expected Result:**  
A validation message should be displayed indicating that email is required.

**Status:**  
Failed

**Related Bug:**  
- Issue #1 – Login form does not validate empty email field
