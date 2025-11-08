# ✅ Test Case

**Test Case ID:** TC-004  
**Title:** Login Form Validation  
**Requirement ID (if exists):**  
**Module / Area:** Authentication  
**Type:** Functional / Negative  
**Priority:** High  
**Severity:** Critical  

**Preconditions:**  
- App installed  

**Environment:**  
- Device: iPhone XS 
- OS version:  18.6.2
- App version:  Threads 405.1
- Network: Wi-Fi or Mobile Data

---

## ✅ Test Steps

| Step | Action | Expected Result |
|------|---------|------------------|
| 1 | Open the app | App opens successfully |
| 2 | Tap "Log in" | Login screen appears |
| 3 | Leave the email field empty | Email field stays blank |
| 4 | Enter any password | Password is accepted in the field |
| 5 | Tap "Log in" | Validation message appears: “Email is required” |
| 6 | Repeat with: invalid email format | Validation: “Invalid email format” |
| 7 | Repeat with: empty password | Validation: “Password is required” |
| 8 | Repeat with: both fields empty | Validation for both fields appears |

---

## ✅ Expected Result

- App shows correct validation messages:  
  - “Email is required”  
  - “Password is required”  
  - “Invalid email format”  
- User cannot log in with invalid data  

---

## ✅ Postconditions

- No login session is created
