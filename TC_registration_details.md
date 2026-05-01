# Test Cases: Registration and Login Module

| TC ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC001 | Valid Registration | Enter valid name, email, password, click register | Account created successfully | | |
| TC002 | Register with existing email | Enter already registered email | Show error "Email already exists" | | |
| TC003 | Register with empty name | Leave name field blank | Show error "Name is required" | | |
| TC004 | Register with invalid email format | Enter "moulali@" as email | Show error "Invalid email format" | | |
| TC005 | Register with weak password | Enter password "123" | Show error "Password too weak" | | |
| TC006 | Register with mismatched passwords | Enter different confirm password | Show error "Passwords do not match" | | |
| TC007 | Valid Login | Enter correct email and password | Login successful, redirect to dashboard | | |
| TC008 | Login with wrong password | Enter incorrect password | Show error "Invalid credentials" | | |
| TC009 | Login with unregistered email | Enter email not in system | Show error "User not found" | | |
| TC010 | Login with empty fields | Click login without entering anything | Show error "Fields cannot be empty" | | |
| TC011 | Forgot password with valid email | Enter registered email in forgot password | Password reset link sent to email | | |
| TC012 | Forgot password with invalid email | Enter unregistered email | Show error "Email not found" | | |
| TC013 | Session timeout | Leave portal idle for 30 minutes | Auto logout with session expired message | | |
| TC014 | Remember me functionality | Check remember me and login | User stays logged in after browser restart | | |
| TC015 | Logout functionality | Click logout button | User logged out and redirected to login page | | |
