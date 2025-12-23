# TC-LOGIN-002 – Invalid Email Format Validation

## Objective
Verify that the login form validates incorrect email formats and prevents submission.

## Preconditions
- User is on the login page
- Application is accessible

## Test Data
- Invalid email examples:
  - test@
  - test.com
  - test@com
- Valid password

## Test Steps
1. Navigate to the login page
2. Enter an invalid email format
3. Enter a valid password
4. Click on the "Login" button

## Expected Result
- A validation message is displayed indicating the email format is invalid
- The form is not submitted

## Actual Result
- (To be filled during execution)

## Status
- Not Executed

## Priority
- High

## Related Bug
- Login form accepts invalid email format

## QA Checklist Reference
- checklists/qa-web-checklist.md
