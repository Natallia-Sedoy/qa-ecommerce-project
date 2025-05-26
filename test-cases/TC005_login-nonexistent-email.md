# TC005 – Login with Nonexistent Email

**Title:** Try to log in with an email that is not registered  
**Precondition:** Email is not in the system  
**Test Steps:**
1. Go to https://automationexercise.com
2. Click on “Signup / Login”
3. Enter an email that was never registered (e.g., `notreal123@example.com`)
4. Enter any password
5. Click “Login”

**Expected Result:** Error message appears: “Your email or password is incorrect!”  
**Postcondition:** User is not logged in
