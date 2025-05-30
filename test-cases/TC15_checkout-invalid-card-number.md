TC15 – Checkout with Invalid Card Number

Title: Submit order with an obviously invalid card number  
Precondition: User is logged in and has product in cart  

Test Steps:
1. Log in to https://automationexercise.com
2. Add any product to the cart
3. Click “Cart” → “Proceed to Checkout”
4. Fill address and proceed to payment
5. Enter:
   - Name on Card: Natallia  
   - Card Number: `1111 2222 3333 4444`  
   - CVC: 123  
   - Expiry: 12/29  
6. Click “Pay and Confirm Order”

Expected Result:  
System should show validation error for invalid card number  

Actual Result:
System accepts invalid card number and completes order

Postcondition: 
Order is placed despite invalid payment data
