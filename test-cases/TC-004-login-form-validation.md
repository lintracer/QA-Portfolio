# TC-004: Login Form Validation

**Area:** Authentication  
**Priority:** High  
**Severity:** Critical  
**Test Type:** Functional / Negative  
**Platform:** iOS / Android  
**Preconditions:**  
- App installed  

---

## ✅ Steps:
1. Open the app  
2. Tap "Log in"  
3. Leave the email field empty  
4. Enter any password  
5. Tap “Log in”  
6. Repeat with:  
   - invalid email format  
   - empty password  
   - both fields empty

---

## ✅ Expected Result:
The app shows validation messages:  
- “Email is required”  
- “Password is required”  
- “Invalid email format”  
User cannot log in with invalid data.
