# SCRUM-8: System allows customer registration with a mobile number already used by another customer

**Severity:** High  
**Status:** Open  
**Environment:** demo.guru99.com/V4 — Chrome Browser, Windows 10  

## Steps to Reproduce
1. Open demo.guru99.com/V4 in a browser
2. Log in to the Manager account
3. Navigate to New Customer
4. Fill in all required fields using a mobile number 
   already registered to an existing customer
5. Press Submit

## Actual Result
The system successfully creates a new customer account 
using a mobile number that is already registered to 
another customer, allowing duplicate phone numbers 
across multiple accounts.

## Expected Result
The system should prevent registration with a mobile 
number already in use and display an
