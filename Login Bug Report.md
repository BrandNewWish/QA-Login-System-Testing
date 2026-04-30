# Bug Report – Login Crash on Invalid Credentials

---

## Title
Web application becomes unresponsive during login with incorrect password

---

## Author
Anya Soimova

---

## Environment
Windows 11  
Chrome 145.0.7632.119  
E-commerce Demo # Bug Report – Login Crash on Invalid Credentials

---

## Preconditions
- User is on login page  
- User has a registered account  

---
## Test Data
- Invalid password  

---

## Description
When the user enters an incorrect password during login and submits the form, the page crashes and becomes unresponsive instead of showing an error message.

---

## Steps to Reproduce
1. Go to login page  
2. Click "Sign in"  
3. Enter valid email  
4. Click "Continue"  
5. Enter incorrect password  
6. Click "Sign in"  

---

## Actual Result
Web application becomes unresponsive and freezes  

---

## Expected Result
Error message should be displayed:
"There was a problem. Your password is incorrect."

User should remain on login page  

---

## Severity
High  

## Priority
High  

## Repeatability
Always
