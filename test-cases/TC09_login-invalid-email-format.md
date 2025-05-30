TC09 – Login with Invalid Email Format

Title: Try to log in with an improperly formatted email  
Precondition: None  
Test Steps:
1. Go to https://automationexercise.com
2. Click on “Signup / Login”
3. Enter email like `abc.com` or `abc@`
4. Enter any password
5. Click “Login”

Expected Result: Validation prevents form submission or shows error  
Postcondition: Login fails
