# TC015 – Order Placement with Invalid Payment Info

**Title:** Attempt to place an order with missing or invalid payment data  
**Precondition:** User is logged in and has item(s) in cart  
**Test Steps:**
1. Log in and go to cart
2. Click “Proceed to Checkout”
3. Skip or enter invalid card data (e.g., empty fields or `1111 2222`)
4. Click “Pay and Confirm Order”

**Expected Result:** Error message is displayed or payment is rejected  
**Postcondition:** Order is not placed
