# QA Testing Portfolio

### Mannual Testing
### Project 1: Amazon Clone Flutter App 

#### Project Overview
This project involves manual testing of key modules of a Flutter-based Amazon Clone application.  
The goal is to verify functionality, identify defects, and ensure proper validation of user inputs.

---

## Modules Covered

### Login Module
- Tested user authentication functionality  
- Verified valid and invalid login scenarios  
- Checked input validation and error handling  

### Add Product Module
- Tested product creation functionality  
- Verified form validations (required fields, invalid inputs)  
- Checked image upload, category selection, and edge cases  

---

## Testing Scope
- Functional Testing  
- Input Validation  
- Error Handling  
- Edge Case Testing  

---

## Bugs Identified

### Login Module
- Runtime error: "null is not a subtype of type String"  
- Missing validation handling  

### Add Product Module
- No validation for negative values (price, quantity)  
- System accepts zero values  
- No validation message for missing image  
- Application crashes on invalid input (Dio exception)  
- No character limit validation for product name  

---

## Test Summary

### Login Module
- Total Test Cases: 8
- Passed: 3 
- Failed: 5 

### Add Product Module
- Total Test Cases: 16  
- Passed: 9  
- Failed: 7  

---

## Tools Used
- Manual Testing  
- MS Excel (Test Cases)  
- MS Word (Bug Reports)  

---

### API Testing
### Project 1: Amazon Clone Flutter App 

#### Project Overview
This project involves API testing of the Signup,Login functionality of the Amazon Clone application using Postman.  
The goal is to validate request/response behavior, status codes, and backend validations.

---

## Modules Covered

## Sign Up

## Bugs Identified

- Incorrect status code returned (500 instead of 400) for validation errors  
- Invalid email formats returning incorrect status codes  
- Duplicate user registration returns wrong status code (400 instead of 409)  
- Password with spaces accepted without validation  
- Special characters in name are not validated  
- Empty JSON request returns server error (500) instead of validation error  

---

## Test Summary

- Total Test Cases: 15  
- Passed: 6
- Failed: 9

---

## Login

## Bugs Identified

- Incorrect error message displayed when email field is missing  
- Incorrect status code (500 instead of 400) when password field is missing  
- Invalid email format returns incorrect error message  
- Unregistered email returns incorrect status code (400 instead of 401/404)  
- Empty JSON request returns incorrect error message  
- Uppercase email not handled correctly during login  
- API accepts extra fields and logs in user successfully without validation  

---

## Test Summary

- Total Test Cases: 11 
- Passed: 4
- Failed: 7

---

## Testing Scope
- Request & Response Validation  
- Status Code Verification  
- Input Validation  
- Error Handling  
- Edge Case Testing  

---

## Tools Used
- Postman (API Testing)  
- JSON  
- MS Excel (Test Cases)  
- MS Word (Bug Reports)  

---
