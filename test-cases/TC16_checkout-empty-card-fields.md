TC16 – Checkout with Empty Payment Fields

Title: Try to place an order with empty payment form  
Precondition: User is logged in and has product in cart  

Test Steps:
1. Log in to https://automationexercise.com
2. Add any product to the cart
3. Proceed to checkout
4. Leave all or any of payment fields empty
5. Click “Pay and Confirm Order”

Expected Result:  
System should block submission and show error messages for required fields  

Actual Result: 
Order is not placed — user remains on the same page ( passes )  

Postcondition: 
No order is created
