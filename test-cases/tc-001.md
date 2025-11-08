# ✅ Test Case

**Test Case ID:** TC-001  
**Title:** Creating a new text post  
**Requirement ID (if exists):**  
**Module / Area:** Posting / Composer  
**Type:** Functional  
**Priority:** High  
**Severity:** Major  

**Preconditions:**  
- User is logged into Threads  
- Internet connection is active  
- App is launched and user is on the Home Feed screen  

**Environment:**  
- Device: iPhone XS (TestFlight build)  
- OS version: iOS 18.6.2
- App version / Browser: Threads (TestFlight)  
- Network: Wi-Fi or Mobile Data

---

## ✅ Test Steps

| Step | Action | Expected Result |
|------|---------|------------------|
| 1 | Tap the **+** button (“New thread”) | Composer opens |
| 2 | Enter valid text (1–500 characters) | Text appears in the input field |
| 3 | (Optional) Add emoji | Emoji are displayed correctly |
| 4 | Tap the **Post** button | App starts publishing the post |
| 5 | Wait for publication | Post publishes successfully without errors |

---

## ✅ Expected Result

- Post is successfully published  
- User is redirected to feed or sees post in their profile  
- Text appears exactly as typed  
- No errors or noticeable delays  

---

## ✅ Postconditions

- New post appears in user’s profile and feed
