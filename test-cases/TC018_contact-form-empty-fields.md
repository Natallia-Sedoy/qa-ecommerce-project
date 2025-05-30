TC018 – Contact Form Submission with Empty Fields (excluding email)

**Title:** Try to submit contact form with only email filled  
**Precondition:** User is on Contact Us page  

**Test Steps:**
1. Go to https://automationexercise.com/contact_us
2. Leave all fields empty except:
   - Email: natalia@gmail.com
3. Click “Submit”
4. Confirm the alert popup

**Expected Result:**  
System should block submission due to missing Name, Subject, and Message  

**Actual Result:**  
Form submits successfully even when required fields are empty — except Email

**Status:** ❌ Failed (see Bug004 – Missing field validation skipped)

**Postcondition:**  
User sees “Success!” even though fields were not filled
