# TC016 – Successful Order Placement and Payment

**Title:** Complete an order with valid payment and shipping details  
**Precondition:** User is logged in and has product(s) in cart  
**Test Steps:**
1. Go to https://automationexercise.com
2. Log in with valid credentials
3. Add a product to the cart
4. Go to “Cart” and click “Proceed to Checkout”
5. Enter valid address details (or confirm saved address)
6. Write a message in the comment box (optional)
7. Click “Place Order”
8. Enter dummy credit card details:
   - Name on Card: `Natallia`
   - Card Number: `4242 4242 4242 4242`
   - CVC: `123`
   - Expiry: `12/29`
9. Click “Pay and Confirm Order”

**Expected Result:** Order is successfully placed, user sees “Your order has been placed successfully!”  
**Postcondition:** Cart is emptied, order is saved to user history
