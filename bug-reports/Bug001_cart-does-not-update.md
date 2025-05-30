Bug001 – Cart Does Not Update Immediately After Adding Product

**Title:** Cart icon in the navigation bar does not reflect added product until page refresh  
**Severity:** Medium  
**Environment:** https://automationexercise.com – Chrome 124 – macOS  

**Steps to Reproduce:**
1. Go to homepage
2. Hover over any product and click “Add to Cart”
3. Click “Continue Shopping”
4. Look at the cart icon (top-right corner)

**Expected Result:**  
Cart icon should show “1” item added (or actual count), immediately after product is added

**Actual Result:**  
Cart icon still shows "0" until page is refreshed or user navigates to cart

**Postcondition:**  
Cart is technically updated, but UI is not synced

**Notes:**  
This may confuse the user and reduce trust in the cart feature.
