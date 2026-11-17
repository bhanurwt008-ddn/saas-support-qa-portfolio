Manual QA Test Execution Report

Project Information

Application: The Internet – Practice Application
Module: Login
Testing Type: Functional Testing
Test Approach: Manual Testing

Test Execution Summary

Test ID| Test Scenario| Expected Result| Actual Result| Status
TC01| Login with valid credentials| User should access Secure Area| Login successful| PASS
TC02| Login with invalid password| Error message displayed| Not tested| NOT EXECUTED
TC03| Login with invalid username| Error message displayed| Not tested| NOT EXECUTED
TC04| Login with empty fields| Validation displayed| Not tested| NOT EXECUTED
TC05| Logout after successful login| User session ends| Not tested| NOT EXECUTED

Detailed Test Case – TC01

Test Scenario: Verify login using valid credentials.

Precondition: Practice application login page is accessible.

Steps Executed:

1. Open the login page.
2. Enter valid username.
3. Enter valid password.
4. Click Login.
5. Verify successful login.

Expected Result: User should successfully access the Secure Area.

Actual Result: Login was successful.

Execution Status: PASS

Execution Summary

- Total test cases listed: 5
- Executed: 1
- Passed: 1
- Failed: 0
- Not Executed: 4

Conclusion

The valid login functionality passed the manual test.

Further negative and boundary testing is pending.

Note: This report records an actual test execution. Remaining test cases have not yet been executed.
