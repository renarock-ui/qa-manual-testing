# Login & Registration – Test Cases

## Preconditions
- User is on the ecommerce web application
- Browser: Chrome
- Internet connection available

---

## Registration

| ID | Scenario | Steps | Expected Result |
|----|--------|------|----------------|
| TC-R-01 | Register with valid data | Enter valid name, email, password → Submit | User account is created |
| TC-R-02 | Register with existing email | Use already registered email | Error message displayed |
| TC-R-03 | Invalid email format | Enter email without @ | Validation error |
| TC-R-04 | Weak password | Enter password < 8 chars | Validation error |
| TC-R-05 | Empty mandatory fields | Submit empty form | Required field messages |

---

## Login

| ID | Scenario | Steps | Expected Result |
|----|--------|------|----------------|
| TC-L-01 | Login with valid credentials | Enter valid email & password | User logged in |
| TC-L-02 | Invalid password | Enter wrong password | Error message shown |
| TC-L-03 | Empty fields | Submit without data | Validation error |
| TC-L-04 | Case sensitivity | Email uppercase | Login successful |
| TC-L-05 | Multiple failed attempts | 5 invalid logins | Account warning / error |
