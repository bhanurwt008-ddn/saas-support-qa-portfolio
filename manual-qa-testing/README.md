Manual QA Testing – SaaS Login Page

Project Overview

This project demonstrates manual testing of a sample SaaS application login page.

Testing Objectives

- Verify successful user login.
- Identify invalid login behaviour.
- Validate email and password fields.
- Test password visibility.
- Verify password recovery functionality.
- Identify potential usability issues.

Test Environment

- Testing Type: Manual Testing
- Application: Sample SaaS Login Page
- Browser: Google Chrome
- Testing Method: Functional Testing

Test Scenarios

ID| Test Scenario| Expected Result
TC01| Login with valid credentials| User logs in successfully
TC02| Login with incorrect password| Error message displayed
TC03| Login with incorrect email| Error message displayed
TC04| Submit empty fields| Required field validation
TC05| Enter invalid email format| Email validation displayed
TC06| Enter password with spaces| Application handles input correctly
TC07| Click show password| Password becomes visible
TC08| Click hide password| Password becomes hidden
TC09| Click forgot password| Password recovery page opens
TC10| Enter unregistered email| Appropriate error displayed
TC11| Check password case sensitivity| Password validation works correctly
TC12| Press Enter to submit login| Login form responds correctly
TC13| Refresh login page| Page loads correctly
TC14| Check login button behaviour| Button responds correctly
TC15| Logout after successful login| User session ends

Bug Report Template

Bug ID: BUG-001

Title: Login button does not respond after entering valid credentials.

Severity: High (sample)

Steps to Reproduce:

1. Open the login page.
2. Enter valid test credentials.
3. Click Login.

Expected Result: User should successfully log in.

Actual Result: Login button does not respond.

Status: Sample – Not an actual verified defect.

Conclusion

This project demonstrates basic manual QA testing techniques, test scenario creation, functional testing and bug documentation.

Note: These are sample test cases. They have not been executed against a live application.
