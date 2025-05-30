TC019 – Contact Form Submission with Improperly Formatted Email

**Title:** Submit contact form with incorrect email format  
**Precondition:** User is on Contact Us page  

**Test Steps:**
1. Fill in all fields correctly except:
   - Email: `abc@` or `abc@com`  
2. Click “Submit”

**Expected Result:**  
Validation error: "Invalid email address"

**Actual Result:**  
Error appears correctly — email is **validated**

**Status:** Passed

**Postcondition:**  
Form is not submitted
