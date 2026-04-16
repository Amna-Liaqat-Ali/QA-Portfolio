# QA Testing Portfolio

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


