TC19 – Contact Form Submission with Improperly Formatted Email

Title: Form should reject submission when email format is invalid  
Precondition: User is on the Contact Us page  

Test Steps:
1. Navigate to https://automationexercise.com/contact_us
2. Fill in all fields as follows:
   - Name: Natallia
   - Email: `abc@` (or `abc@com`)
   - Subject: Test Subject
   - Message: This is a test message.
3. Click “Submit”
4. Click “OK” on alert (if shown)

Expected Result:  
The system detects the incorrect email format and prevents form submission.  
An alert or validation message appears, indicating invalid email format.

Actual Result: 
System blocks submission and shows an error message — works as expected.

Status: Passed

Postcondition:  
Form is not submitted with invalid email.
